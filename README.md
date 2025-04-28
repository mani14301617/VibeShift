![Screenshot 2025-04-28 125303](https://github.com/user-attachments/assets/eeb08982-acee-4857-95e1-7c426bdc74f1)# Real-Time Audio Processing on DSP 6416T

We implemented real-time audio effects using the **TMS320C6416T DSP** platform and **Code Composer Studio**. This project focused on designing and optimizing digital signal processing algorithms to create various audio effects in real-time.
![Uploading Screenshot 2025-04-28 125303.png…]()
## Implemented Effects

- **Robotic Voice**  
  Applied amplitude modulation and spectral shaping techniques to synthesize a mechanical, metallic voice texture.

- **Dark Phonk**  
  Designed deep bass enhancement, intentional distortion, and selective frequency filtering to recreate the dark, gritty soundscape characteristic of the Phonk music genre.

- **Walkie Talkie Effect**  
  Simulated narrow-band communication audio by applying band-pass filtering and dynamic range compression to mimic traditional walkie-talkie sound characteristics.

- **3D Audio Effect**  
  Created spatial audio perception by manipulating interaural time differences (ITD) and amplitude panning, providing an immersive stereo experience.

## Tools and Skills

- **Platform**: TMS320C6416T DSP Starter Kit (DSK6416T)
- **Software**: Code Composer Studio (CCS)
- **Techniques**:
  - Real-time fixed-point DSP programming
  - Audio codec configuration and control
  - Real-time signal path optimization
  - Algorithm design for audio effects


## Future Improvements

- Adding more effects like pitch shifting, reverb, and chorus
- Porting algorithms to floating-point DSPs
- Optimizing memory and execution cycle usage for larger effect chains
