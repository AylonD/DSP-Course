# DSP-Course
As part of an introductory signal processing course at the university, we were assigned with a signal processing project that combines sound processing and the use of adaptive filters.

# PART A:
In a hall measuring 30x30 meters, a resonance is created whose transit time is 0.1 seconds. In each encounter with the wall the return intensity is 0.5 and the phase is 180 degrees.
In addition there is a noise (generated before the resonance) Gaussian concentrated around 600 Hz with a standard deviation of 200 Hz. The noise level is 10% of the 
signal strength.

    1. Create an impulse response that characterizes the resonance. Stop the reaction when the resonance intensity drops below 10%.
    2. Record two audio clips in your voice tonight.
    3. Add the Gaussian noise to both - Upload the source files and the files with the noise.
    4. Add the Resonance - Upload the files.
    5. Use LMS prepared on one of the files to clean both. Upload:
        A. The cleaned files
        B. The report states the filter coefficients.
 # PART B:
    1. Duplicate one of the original files from section 2 in the cosine at 150 Hz.
    2. Pass it in a high-pass filter with a trimmer at 200 Hz - upload the file
    3. Add the noise and resonance and upload the file.
    4. Recover the file using rls filter - and upload the recovered file
# PLOTS:
# Recordings' plots
![image](https://github.com/AylonD/DSP-Course/assets/101047444/e1489fdc-37ad-45bc-a8e0-7aee6247df12)

# Gaussian White Noise
![172313584-11ac5a75-dc79-459a-bc88-1e2b3d352b1f](https://user-images.githubusercontent.com/101047444/190337415-08f89ffd-77db-48fc-a305-4e07a711c9cf.png)

# Recordings with Noise
![image](https://github.com/AylonD/DSP-Course/assets/101047444/aa3c14fe-2778-49cf-92d4-b37cd4c6d238)

# Correaltion function between recording and echoFx
![image](https://github.com/AylonD/DSP-Course/assets/101047444/cc4e86aa-9ba9-4a48-948c-84afac451e77)
![image](https://github.com/AylonD/DSP-Course/assets/101047444/f999be96-f530-4107-8d37-2592c69a09e8)

# LMS Filter
![image](https://github.com/AylonD/DSP-Course/assets/101047444/afab5e15-2f1a-45f7-aaaa-5d84ed541fa0)

# Recordings filtered by LMS Adaptive Filter
![image](https://github.com/AylonD/DSP-Course/assets/101047444/803f6944-935c-48fd-ad0e-fb702d676600)
![image](https://github.com/AylonD/DSP-Course/assets/101047444/055a7ef8-68a8-4f84-b4a8-ed97ccce5cc2)


# Modulator Signal
![image](https://github.com/AylonD/DSP-Course/assets/101047444/26ba1778-d182-44de-ac00-fd9d4863b89d)

# Modulated Signal
![image](https://github.com/AylonD/DSP-Course/assets/101047444/594d9282-b226-4cbd-b800-23f4e7e87952)

# Filtere'd signal 
![image](https://github.com/AylonD/DSP-Course/assets/101047444/9445de0e-9fa5-4ab5-b13d-29f5189cdf23)

# Echoed & Noisy Voice (After HPF)
![image](https://github.com/AylonD/DSP-Course/assets/101047444/fc6c2c95-4fdf-4835-930e-69a78944d853)

# RLS adaptive filter
![172314315-58365233-acf0-4424-bcff-af70cc4fe4e2](https://user-images.githubusercontent.com/101047444/190338007-11789edd-2c9b-420a-9a20-bf64a74d8481.png)

# Autocorrelation of original voice after RLS filter
![image](https://github.com/AylonD/DSP-Course/assets/101047444/4cf0d091-6db5-45e1-87ba-2c1f889c76c2)

