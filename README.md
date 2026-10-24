<h1 align="center">Pratul Deshpande</h1>

<p align="center">
  <b>Quantum · Electronics · AI</b><br>
  Embedded systems and software developer · E&amp;Tc undergraduate
</p>

<p align="center">
  <a href="https://pratuldeshpande.com"><img src="https://img.shields.io/badge/Website-pratuldeshpande.com-050505?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/pratuldeshpande"><img src="https://img.shields.io/badge/LinkedIn-pratuldeshpande-050505?style=flat-square" alt="LinkedIn"></a>
  <a href="https://pypi.org/project/qiskit-waveform-sim/"><img src="https://img.shields.io/pypi/v/qiskit-waveform-sim?style=flat-square&color=050505&label=PyPI" alt="PyPI"></a>
</p>

---

I build software that sits close to hardware: firmware for microcontrollers, cryptography that runs on them, and tools for the control layer of quantum computers. Most of my projects start where a library stops working for a real device or a new version.

## Projects

### [qiskit-waveform-sim](https://github.com/PratulDeshpande/qiskit-waveform-sim)
<a href="https://github.com/PratulDeshpande/qiskit-waveform-sim"><img src="https://img.shields.io/badge/Qiskit-Ecosystem-6929C4?style=flat-square" alt="Qiskit Ecosystem"></a>
<img src="https://img.shields.io/badge/Python-3.11%2B-050505?style=flat-square&logo=python&logoColor=white" alt="Python 3.11+">

Offline control-waveform simulator and interactive pulse sheet for Qiskit 2.5+. Qiskit 2.0 removed `qiskit.pulse`, so this rebuilds DRAG and GaussianSquare envelopes from a scheduled circuit's gates and `Target` durations, then plots them as a pulse sheet and an I/Q oscilloscope. Listed in the Qiskit Ecosystem.

```bash
pip install qiskit-waveform-sim
```

### [PQCMicro](https://github.com/PratulDeshpande/PQCMicro)
<img src="https://img.shields.io/badge/C%2FC%2B%2B-050505?style=flat-square&logo=cplusplus&logoColor=white" alt="C/C++">
<img src="https://img.shields.io/badge/ESP32%20·%20STM32%20·%20RP2040-050505?style=flat-square" alt="ESP32, STM32, RP2040">

NIST post-quantum cryptography for microcontrollers. ML-KEM-512 (FIPS 203) key exchange and ML-DSA-44 (FIPS 204) signatures, ported from PQClean, with FreeRTOS-aware tasks on ESP32, NVS key storage, and key chunking for LoRa and BLE packet limits. Installs from the Arduino Library Manager, PlatformIO, or the ESP-IDF Component Manager.

### [IonFiltra](https://github.com/PratulDeshpande/IonFiltra)
<img src="https://img.shields.io/badge/IIoT-full%20stack-050505?style=flat-square" alt="IIoT full stack">
<a href="https://ionfiltra.pratuldeshpande.com"><img src="https://img.shields.io/badge/Live-demo-050505?style=flat-square" alt="Live demo"></a>

Industrial IoT platform for monitoring and predictive maintenance of pulse-jet bag filter controllers. STM32 nodes read controllers over Modbus RTU and relay over LoRa to an ESP32 gateway on GSM. A Node.js and PostgreSQL backend streams live data to a React dashboard, and Gemini runs daily failure analytics plus a RAG assistant that answers questions from equipment manuals and live readings.

## Toolbox

| Area | Tools |
| --- | --- |
| Languages | C, C++, Python, JavaScript |
| Embedded | ESP32, STM32, RP2040, FreeRTOS, ESP-IDF, PlatformIO, Modbus RTU, LoRa, UDS |
| Quantum | Qiskit, OpenQASM 3, QuEST |
| Web and data | Node.js, Express, React, Vite, Tailwind CSS, PostgreSQL |
| AI | Gemini, retrieval-augmented generation |

---

<p align="center"><sub>Open to collaborations on quantum software, embedded security, and IIoT. Reach me through <a href="https://pratuldeshpande.com">pratuldeshpande.com</a>.</sub></p>
