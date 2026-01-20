# BCI_VLA
This project serves as a demonstration and verification system for the alignment and implantation puncture process of electrodes for brain-computer interface (BCI) implantation.  
The figure below is a schematic diagram of this project. As illustrated, the end-effector of the brain-computer interface (BCI) implantation manipulator is an implantation needle, which is used to implant the electrode ring (the small hole shown in the figure) at the tip of the flexible electrode into the target site. This flexible electrode is based on a slender metal sheet and features an extremely small actual size — the flexible electrode wire has a length of approximately 3 cm, a width of about 80 μm and a thickness of around 10 μm, while the size of the electrode ring at its tip is merely 30×50 μm. For this reason, the entire operational process of the project must be conducted under a microscopic vision system.
<img width="2816" height="1536" alt="Gemini_Generated_Image_emb6ybemb6ybemb61" src="https://github.com/user-attachments/assets/faf73de2-4def-4c30-84fa-e47c103f2132" />

The video below fully demonstrates the complete process of electrode implantation. To ensure authenticity, we captured the screen using an external camera device. On one hand, the terminal interface displayed on the computer screen shows the entire procedure of the large model capturing real-time images, performing inference, and generating corresponding outputs. On the other hand, the information panel embedded in the background of the brain-computer interface (BCI) system software synchronously displays the action function currently being executed. 


https://github.com/user-attachments/assets/35b8504d-96fa-429b-bbc6-b213a7c44359


  As can be seen from the demonstration, the entire workflow consists of three core actions, namely ADJUST_EXPOSURE, ADJUST_FOCUS and ALIGN_NEEDLE, executed in sequence. Specifically, ADJUST_EXPOSURE is designed to adjust exposure parameters, which renders the field of view clear and bright to meet the requirements of surgical operations. ADJUST_FOCUS drives the displacement of the microscopic camera to achieve precise focusing on the needle tip, laying a solid foundation for subsequent procedures. Finally, the system completes the status verification and permits the execution of ALIGN_NEEDLE after confirming that all conditions are correct.

Due to the file size limitations imposed by GitHub on video uploads, we have compressed the demonstration video, which has resulted in a certain degree of blurriness in the video quality. To compensate for this, we have supplemented a number of screenshots capturing the key operation steps, and please refer to the figures below for details.

![extracted_frame](https://github.com/user-attachments/assets/1936af1f-1eb9-4d9f-aea3-c1faebf98713)

  This figure depicts the system status after all three actions have been fully executed.

  <img width="3840" height="2880" alt="image" src="https://github.com/user-attachments/assets/b068680a-6265-4f0e-b3b5-cf78710cd5ac" />

  This figure corresponds to the live scene of the electrode implantation operation. Due to the extremely slender size of the needle tip, a certain degree of blurriness exists in the focusing during imaging. To address this, we supplemented a set of higher-definition live images taken after the implantation operation was fully completed, as shown below.

![DSC06056](https://github.com/user-attachments/assets/fc51cc5f-4c6b-42b7-8578-ab5ca35fce4c)

  ![DSC06075](https://github.com/user-attachments/assets/1e329079-04ba-4733-9b5f-e6b57bc8720d)
  ![DSC06094](https://github.com/user-attachments/assets/7c1347dc-855b-4267-b0cb-aab58f588abb)
  ![DSC06058_compressed](https://github.com/user-attachments/assets/a5e64159-d92d-46b6-b7ce-3a347de261cf)
  <img width="1268" height="840" alt="image" src="https://github.com/user-attachments/assets/e7e751d4-04bd-4d08-9413-622813d0c323" />

  <img width="1280" height="848" alt="image" src="https://github.com/user-attachments/assets/875d1eb3-7de6-48ba-9f5c-9a881c03f4f0" />
  <img width="988" height="810" alt="image" src="https://github.com/user-attachments/assets/83a56499-7ba9-4eef-9538-94b6a963d71e" />

