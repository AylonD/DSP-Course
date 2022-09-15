# DSP-Course
As part of an introductory signal processing course at the university, we were asked to do a project on signal processing that combines sound processing and the use of adaptive filters.

# PART A:
In a hall measuring 30x30 meters, a resonance is created whose transit time is 0.1 seconds. In each encounter with the wall the return intensity is 0.5 and the phase is 180 degrees.
In addition there is a noise (generated before the resonance) Gaussian concentrated around 600 Hz with a standard deviation of 200 Hz. The noise level is 10% of the 
signal strength.

    1. Create a shock response that characterizes the resonance. Stop the reaction when the resonance intensity drops below 10%.
    2. Record two audio clips in your voice tonight.
    3.Add the Gaussian noise to both - Upload the source files and the files with the noise.
    4. Add the Resonance - Upload the files.
    5.Use lms prepared on one of the files to clean both Upload:
        A. The cleaned files
        B. The report states the filter coefficients.
 # PART B:
    1. Duplicate one of the original files from section 2 in the cosine at 150 Hz.
    2. Pass it in a high-pass filter with a trimmer at 200 Hz - upload the file
    3. Add the noise and resonance and upload the file.
    4. Recover the file using rls filter - and upload the recovered file
# PLOTS:
# Recording plot
![172313544-a50c3f92-4a73-4bef-8996-88a2b2da54cf](https://user-images.githubusercontent.com/101047444/190337287-d70c3801-d470-4bac-8e62-8fdb5b2d5a64.png)

# Gaussian White Noise
![172313584-11ac5a75-dc79-459a-bc88-1e2b3d352b1f](https://user-images.githubusercontent.com/101047444/190337415-08f89ffd-77db-48fc-a305-4e07a711c9cf.png)

# Record with Noise
![172313658-4ff22ff0-358d-4415-a57a-3d93b09a5dab](https://user-images.githubusercontent.com/101047444/190337526-9f1f98d1-b67d-482a-bbdf-a46bf642aaa7.png)

# Correaltion function between recording and echoFx
![172313761-ec673d13-3c0f-483d-a432-95f2398ace85](https://user-images.githubusercontent.com/101047444/190337603-9cdf4ff0-f01e-4526-af20-c275de77f67c.png)

# LMS Filter
![172313803-611252fc-e0be-45ab-8c3c-beabcacfe985](https://user-images.githubusercontent.com/101047444/190337681-49d82ef5-2193-4e1b-bee3-7aed0d1d7a65.png)

# Recording filtered by LMS Adaptive Filter
![172313956-a949ff83-4c38-4847-870d-674599f843a5](https://user-images.githubusercontent.com/101047444/190337750-64509a16-f8ba-435f-bf8e-6eb51fe428cd.png)

# Modulator Signal
![172314068-0fb24506-ae99-4053-810b-713d7c4d71b7](https://user-images.githubusercontent.com/101047444/190337835-1b8206af-25cb-4bdb-ad5c-167cebabcfa3.png)

# After High Pass Filter
![172314151-f1036696-6b4e-4c69-94f3-4758459a6d45](https://user-images.githubusercontent.com/101047444/190337889-21674ebc-b9d7-4df8-a0d0-e22575212059.png)

# Echoed & Noisy Voice (After HPF)
![172314260-cc78c808-f5b9-4308-b5fd-5ef0d4fa4194](https://user-images.githubusercontent.com/101047444/190337965-551e5533-d5c3-49cd-8390-ddc52cb77448.png)

# RLS adaptive filter
![172314315-58365233-acf0-4424-bcff-af70cc4fe4e2](https://user-images.githubusercontent.com/101047444/190338007-11789edd-2c9b-420a-9a20-bf64a74d8481.png)

# Autocorrelation of original voice after RLS filter
![172314438-999d976b-399d-4ab3-8ac2-d6a432101585](https://user-images.githubusercontent.com/101047444/190338099-7660e88f-1033-4aa5-b530-7fbd530e348d.png)




