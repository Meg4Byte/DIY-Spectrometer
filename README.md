# Spectrometer
Homemade DIY spectrometer using FOSS Theremino Software , usb camera and some ingenuity

## Intro 

- [Project Description](#project-description)
- [But What is a Spectrometer?](#but-what-is-a-spectrometer)
- [How to Build Your Own Spectrometer](#how-to-build-your-own-spectrometer)
  - [Materials Needed](#materials-needed)
  - [Step by Step Instructions](#step-by-step-instructions)
  - [Usage Instructions](#usage-instructions) 
- [Results](#results)
- [Contributions](#contributions)
- [Licence](#licence)
- [Contact](#contact)
  

## Project Description 
This project demonstrates how to create a DIY   spectrometer using open-source Theremino software, a USB camera, and easily accessible materials. It's a fantastic way to delve into the world of spectroscopy and explore the spectrum of light in a hands-on manner.

## But What is a Spectrometer?

A spectrometer is an instrument used to measure properties of light over a specific portion of the electromagnetic spectrum. It works by dispersing light into its component wavelengths, allowing for the analysis of different properties such as intensity, wavelength, and more.

The following diagram illustrates the basic working principle of a spectrometer


![spectr_principle](https://github.com/Meg4Byte/Spectrometer/assets/121357383/48567232-f5ac-4c01-af24-f59dfd9d1e06)


1. **Light Source**: The spectrometer starts with a light source, which emits light that passes through a slit.
2. **Collimator**: The light then passes through a collimator, which makes the light rays parallel.
3. **Diffraction Grating**: These parallel rays then hit a diffraction grating (or prism) which disperses the light into its component wavelengths.
4. **Detector**: Finally, these dispersed light rays are captured by a detector (like a camera), which records the spectrum.


## How to Build Your Own Spectrometer

#### Materials Needed
- USB camera (used as a detector)
- Compact disc (CD) or DVD (used as a diffraction grating)
- Black tape and cardboard
- FOSS Theremino software
- Computer with any windows OS (7+) 
- Box (shoebox will do just fine)
- Light source (I have used white LED flashlight) 

#### Step by Step Instructions

Prepare the CD: Carefully cut a piece from the CD to use as a diffraction grating. The reflective surface will help in dispersing light.
Modify the Camera: Attach the CD piece to the USB camera lens using black tape or cardboard to hold it in place. Ensure it’s positioned correctly to capture the light spectrum.
Install Theremino Software: Download and install the Theremino software from their official website. This software will process the captured images and help analyze the light spectrum.
Assemble the Spectrometer: Connect the USB camera to your computer, and set up the Theremino software to interface with the camera. Position the camera to capture light from a source, and adjust the setup to ensure a clear spectrum is visible.

#### Usage Instructions

- Start the Software: Launch the Theremino software on your computer.

- Capture the Spectrum: Point the USB camera towards a light source, and adjust until the spectrum is clearly visible in the software interface.
  
- Analyze the Data: Use Theremino to analyze the captured spectrum, identifying different wavelengths and their intensities.

Note:You may need to calibrate theremeino spectrometer based on the camera.Please refer to the theremenio spectrometer page for more details.

## Results 

Image below represents theoretical spectre of the white LED light source used in this project.X axis is wavelenght in nm and Y axis is presence (green color is most present) 
<p align="center">
  ![white-led-spectrum-768x360-2634762087](https://github.com/Meg4Byte/Spectrometer/assets/121357383/3ff6c714-3e7a-4b90-9f2f-b8fcefb12ac4)
</p>
Here is the measured spectre of the white LED light source.As you can see result are quite similar.

   ![0_15](https://github.com/Meg4Byte/Spectrometer/assets/121357383/51b78181-9099-49b3-ae1e-b044c51142d0)


## Contributions 

Contributions are always welcome! Since this is a homemade project If you have ideas for improvements or additional features, please open an issue or submit a pull request.

## Licence
  This project is licensed under the MIT License. You are free to use, modify, and distribute this code at your own discretion.

## Contact 

  For questions or feedback, feel free to reach out at petnenadd_d@uns.ac.rs .
