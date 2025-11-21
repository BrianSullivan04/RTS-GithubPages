# Real-Time System Conveyor Belt Package Detector

Welcome to my GitHub Pages site!  
Below is a brief demo video showcasing the project.

---

## 🎥 Demo Video

<div align="center">

<!-- Replace with your YouTube video ID -->
<iframe width="560" height="315" 
        src="https://www.youtube.com/embed/R5v5lfN7zVE"
        title="YouTube video player" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>

</div>

---

## 📄 Description

This project implements a real-time safety monitor for a conveyor system using the ESP32 and FreeRTOS. The system continuously measures distance with an ultrasonic sensor and listens for emergency-stop input through an ISR. Hard-deadline tasks ensure the conveyor halts within a guaranteed response window whenever an object or person enters the danger zone. Soft-deadline tasks handle non-critical features such as heartbeat signaling and serial output. The project demonstrates deterministic scheduling, interrupt-driven safety logic, and the practical integration of sensor processing in a real-time environment.