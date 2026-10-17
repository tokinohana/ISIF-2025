# Machine Learning-Powered Mosquito Control System

A student-led engineering and research project developed at **Canisius College, Jakarta, Indonesia**, exploring the application of embedded computing, computer vision, and machine learning for localized mosquito control in urban drainage environments.

**Achievement: Gold Medal — International Science and Invention Fair (ISIF) 2025**

## Overview

Mosquito populations around the Menteng area of Jakarta presented an environmental and public health concern for our school community. Drainage channels and culverts were potential mosquito breeding habitats, motivating our team to explore a technology-driven approach to localized mosquito detection and control.

Developed collaboratively with fellow students at Canisius College, this project combined embedded computing, infrared imaging, computer vision, and an electrically activated mosquito-control mechanism into a physical proof of concept.

The prototype used a Raspberry Pi 5 as its central computing unit and was housed in a custom enclosure made from acrylic and cardboard. Our work was also documented in a research paper titled *Machine Learning Powered Mosquito Population Control System for Sewage Networks*, which explored the broader potential of deploying machine learning-based mosquito-control systems in urban drainage infrastructure.

The project received a **Gold Medal at ISIF 2025**, recognizing our team's work in science, engineering, and technological innovation.

## System Architecture

The prototype was designed around an automated detection-and-response workflow.

1. **Infrared imaging:** An infrared camera observes the surrounding environment, supporting operation in low-light conditions.
2. **Computer vision:** A vision model running on the Raspberry Pi processes camera input to identify potential mosquito targets.
3. **Relay-controlled activation:** The software uses a relay module to control the electrical mosquito-control mechanism following detection.
4. **Physical response:** An electrical mesh adapted from a mosquito racket serves as the prototype's target-control mechanism.

The high-level system architecture is:

`Infrared Camera → Raspberry Pi 5 → Vision Model → Relay Control → Electrical Mesh`

The accompanying research paper also proposed additional safety mechanisms, including water-level monitoring, as well as a more robust enclosure for potential deployment in drainage networks. These were proposed design considerations rather than verified features of the physical prototype.

## Hardware

| Component | Purpose |
|---|---|
| Raspberry Pi 5 (8 GB RAM) | Main computing and control unit |
| 128 GB NVMe SSD | System storage and application environment |
| Raspberry Pi M.2 HAT+ | NVMe storage interface |
| Raspberry Pi cooling fan | Thermal management |
| Infrared camera | Observation in low-light environments |
| Relay module | Software-controlled electrical switching |
| Electrical mesh adapted from a mosquito racket | Physical mosquito-control mechanism |
| Acrylic and cardboard | Custom prototype enclosure |

The hardware was assembled to connect the computing, sensing, and electrical subsystems into a single experimental platform. The Raspberry Pi handled the software-side processing and control logic, while the relay provided the interface between software decisions and the physical mechanism.

## Software and Technologies

- **Python** — application logic and hardware-control integration
- **Raspberry Pi OS / Linux** — embedded computing environment
- **Computer vision and machine learning** — visual target detection
- **GPIO and relay control** — software-to-hardware interaction
- **Raspberry Pi 5** — edge-computing platform

The research paper discusses lightweight convolutional neural networks and YOLO-family object detection models as possible approaches for mosquito recognition on edge devices. The exact model, library versions, and implementation details of the original prototype are not available in this repository.

## My Contributions

I worked alongside my peers on the development of the prototype, with my primary responsibilities focused on **electrical integration, software development, and embedded systems integration**.

### Electrical Wiring and Hardware Integration

- Handled electrical wiring to integrate the prototype's electronic components.
- Worked on integrating the relay-controlled switching mechanism with the system's control logic.
- Helped connect the computing and electrical subsystems into a unified proof of concept.
- Contributed to the physical integration of the electrical mesh into the custom enclosure.

### Software Development

- Developed the Python software running on the Raspberry Pi 5.
- Worked on integrating infrared camera input, computer vision-based detection, and hardware control.
- Developed software-side logic connecting detection results to relay activation.
- Worked within an embedded Linux environment, using the Raspberry Pi's onboard computing resources.

### Embedded Systems Integration

My work focused on connecting the individual components into an integrated system, bridging camera input, computational processing, control logic, and physical actuation.

This required working across software and electronics, with an emphasis on translating a machine learning-based concept into a physical engineering prototype.

## Research and Design

The accompanying research paper, *Machine Learning Powered Mosquito Population Control System for Sewage Networks*, explored how the initial prototype's concept could be extended to urban drainage infrastructure.

The broader research direction considered:

- Edge inference on a Raspberry Pi 5 without requiring cloud processing.
- Infrared imaging for mosquito observation in low-light environments.
- Lightweight object detection models suitable for embedded hardware.
- Environmental sensing and water-level-based safety interlocks.
- Potential deployment of interconnected mosquito-monitoring units across urban drainage networks.

The research also identified engineering challenges, including distinguishing mosquitoes from other objects, validating detection accuracy, protecting electronics from moisture, and ensuring reliable long-term operation.

The physical prototype served as an initial exploration of these ideas, while the research paper established a broader direction for further development.

## Achievement

**Gold Medal — International Science and Invention Fair (ISIF) 2025**

Our team received a Gold Medal at ISIF 2025 for this project. The achievement marked an important milestone in our collaborative work at Canisius College, bringing together research, software development, electronics, and physical prototyping to investigate a practical environmental problem.

## Project Status and Limitations

This project was developed as a proof of concept rather than a production-ready pest-control device.

The prototype explored the integration of computer vision, embedded computing, electrical control, and a custom physical enclosure. It was not a validated solution for reducing mosquito populations or preventing mosquito-borne diseases at scale.

The original Python source code was stored on a Raspberry Pi 5 and is no longer available. As a result, this repository documents the project's concept, hardware architecture, research direction, and engineering contributions rather than providing a reproducible software implementation.

Further development would require recreating the software, validating the detection model against real-world data, and conducting controlled tests of detection performance, reliability, and electrical safety.

## Team

This project was developed collaboratively by students at **Canisius College, Jakarta, Indonesia**. The work combined student-led research, software development, electrical integration, and physical prototyping to explore a technology-based approach to mosquito control.

The team's accompanying research paper documents the broader investigation into machine learning-powered mosquito population control in urban sewage networks.

## Acknowledgements

We thank the faculty and staff of Canisius College for their guidance and support throughout the research and development process.
