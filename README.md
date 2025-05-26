# Network Feedback Application - System Design Documentation

## Overview
This repository contains the system design and UML modeling documentation for the QoE (Quality of Experience) Collection Application, developed as part of the Internet and Mobile Programming course (CEF440) at the University of Buea.

## Document Purpose
This documentation serves as the system design phase following the requirement analysis conducted in Task 3. It translates the identified functional and non-functional requirements into concrete architectural specifications through comprehensive UML modeling.

## Contents

### 1. UML Diagrams
- **Use Case Diagram** - Shows interactions between User, ISP, and Server
- **Sequence Diagrams** (3 diagrams):
  - Login/Register Sequence
  - Feedback Submission Process
  - Offline Data Synchronization
- **Data Flow Diagrams** - Context, Level 1, and Level 2 data flows
- **Class Diagram** - Static structure and entity relationships
- **Deployment Diagram** - Physical component distribution

### 2. System Architecture
- Mobile-first React Native application
- Firebase backend infrastructure
- Modular, service-oriented design
- Privacy-first data handling approach

### 3. Key Features Modeled
- Background network metrics collection
- User feedback submission system
- Offline data storage and synchronization
- Multi-provider network support
- Location-based quality assessment
- Anonymous user identification

## Requirements Traceability
This system design directly addresses:
- **10 Functional Requirements (FR1-FR10)** from Task 3
- **10 Non-Functional Requirements (NFR1-NFR10)** from Task 3
- **MVP prioritization framework** (Must-Have, Should-Have, Could-Have)

## Technical Stack Reflected in Design
- **Frontend:** React Native
- **Backend:** Firebase (Authentication, Firestore, Storage)
- **Development:** Expo, Redux, Jest
- **Design:** Material Design Components

## Next Steps
This system design documentation serves as the foundation for:
1. **Implementation Phase** - Detailed coding based on architectural specifications
2. **Testing Strategy** - Test cases derived from sequence diagrams and requirements
3. **User Interface Design** - UI/UX implementation guided by use case flows
4. **Deployment Planning** - Infrastructure setup based on deployment diagrams

## Related Documents
- **Task 3:** Requirement Analysis Report (prerequisite)
- **Future Tasks:** User Interface Design, Frontend and Backend Implementation, Deployment

**University of Buea**  
Faculty of Engineering and Technology  
Internet and Mobile Programming (CEF440)  
Dr. Nkemeni Valery
