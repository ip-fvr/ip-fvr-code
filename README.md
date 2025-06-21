# IP-FVR

## 🎬 Introduction

This repository is the official implementation of Show and Polish: Reference-Guided Identity Preservation in Face Video Restoration.



## **✨**News and ToDo List

- [ ] Release checkpoints.
- [ ] Release code & data.
- [X] [2025-06-19] Init repository.


## Qualitative Experiments

**Reference face scale**
![](./assets/reference_size.png)
**Observation:** When conducting inference with IP-FVR, more reference faces can lead to higher identity preservation in the restored results.


**Misaligned reference**
<table style="width:100%">
  <tr>
    <td style="width:45%">
      <video src="https://github.com/user-attachments/assets/c189d193-956e-4566-af7f-20c9f48a8859" controls  autoplay style="width:100%">
      </video>
    </td>
    <td style="width:45%">
      <video src="https://github.com/user-attachments/assets/81a196ff-b4b7-4f39-a73c-fcbaaebabdce" controls autoplay style="width:100%">
      </video>
    </td>
  </tr>
</table>










<table style="width:100%">
  <tr>
    <td style="width:45%">
      <img src="assets/peele-1.png" alt="Reference Image 1" style="width:100%">
    </td>
    <td style="width:45%">
      <img src="assets/peele-2.png" alt="Reference Image 2" style="width:100%">
    </td>
  </tr>
</table>

**Observation:** When the reference image is misaligned with the low-quality input video face (e.g., differences in beards), it can affect the results as shown on the right side of the figure above. However, this can be mitigated in practical applications by selecting a more aligned reference image or using facial feature text prompts.
