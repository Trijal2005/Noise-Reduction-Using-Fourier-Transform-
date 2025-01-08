# Noise-Reduction-Using-Fourier-Transform-
**📶 Noise Reduction using Fourier Transform**    This project removes noise from audio signals using Fourier Transform, improving clarity for speech recognition and other applications.

---
## 📖 Introduction

This project showcases how Fourier Transform techniques can be employed to enhance audio signals by reducing noise. By filtering noise frequencies, the processed signals become clearer and more robust, especially in speech recognition applications.

---

## 🚀 Algorithm

1. **Load Audio Data**: Import the audio file for processing.  
2. **Apply Fourier Transform**: Use Fast Fourier Transform (FFT) to convert the signal from the time domain to the frequency domain.  
3. **Analyze Noise**: Identify and estimate the noise profile by analyzing amplitude components.  
4. **Remove Noise**: Subtract the noise profile from the audio's frequency spectrum.  
5. **Reconstruct Signal**: Perform an Inverse Fourier Transform to convert the signal back to the time domain.  
6. **Output**: Obtain the noise-reduced audio signal.

---

## 🛠️ Implementation

The project leverages the following technologies:  
- **Python** for audio processing and mathematical operations.  
- **NumPy** for Fast Fourier Transform (FFT) and signal manipulations.  
- **Matplotlib** for visualizations of audio signals.  

---

## 📊 Results

### Before Noise Reduction(Orginal):
![image](https://github.com/user-attachments/assets/c50cf822-a2ac-4dff-8004-e0a982a259b0)

### With Noise Added:
![image](https://github.com/user-attachments/assets/4d49efb4-935b-45de-92cf-f4dd483d7ea7)


### After Noise Reduction:
![image](https://github.com/user-attachments/assets/dc8185ee-cf61-4141-a060-a2b4c043b3f8)

---

## 🎯 Applications

- Enhancing speech recognition in noisy environments.
- Preprocessing audio data for machine learning models.
- General-purpose audio clarity improvements.

---
## 📚 References

- Fast Fourier Transform (FFT) theory.
- Applications of signal processing in speech recognition.

---
