---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Pixel COG Documentation"
  text: "Processes and services provided by Pixel COG"
  actions:
    - theme: brand
      text: Begin
      link: /markdown-examples

features:
  - icon:
      src: /KNIGHT.png
    title: Knight
    details: Manages all aspects of user authentication and authorization. This includes user registration, login, JWT issuance and validation, OAuth flows, Role-Based Access Control (RBAC), and permission management
  - icon:
      src: /PROFILE.png
    title: Profile Service
    details: Stores and manages user-specific profile data and preferences that are not directly related to authentication. This includes user demographics (name, contact information), notification preferences (email, SMS, push enablement, frequency), and profile picture metadata
  - icon:
      src: /PAPER_PLANES.png
    title: Paper Plane
    details: Handles all outgoing user notifications across various channels transactional emails (registration confirmation, password reset, appointment scheduled/reminder/finished), SMS messages, and push notifications
  - icon:
      src: /TELEPHONE.png
    title: Appointment
    details: Manages the entire lifecycle of appointments. This includes scheduling, booking, cancellation, doctor availability management, and maintaining a history of patient appointments
  - icon:
      src: /BOOK.png
    title: Patient Medical History
    details: Acts as the central repository for a patient's long-term, aggregated medical history. This includes static medical data (allergies, chronic conditions, past diagnoses), and aggregated summary of past treatments. It does not store individual appointment notes
  - icon:
      src: /NOTES.png
    title: Clinical Notes
    details: Stores detailed clinical notes and annotations made by doctors specific to an individual appointment. This service maintains the granular, time-stamped records of doctor-patient interactions during consultations
  - icon:
      src: /PAPER.png
    title: Prescription
    details: Manages the creation, storage, retrieval, and download of medical prescriptions issued by doctors. It ensures proper formatting and accessibility of prescription documents
  - icon:
      src: /DISK.png
    title: File Storage
    details: Provides an API wrapper for handling all file uploads and downloads within the platform. This includes patient-uploaded images (e.g., for video calls), prescription PDFs, and profile pictures
  - icon:
      src: /LENS.png
    title: Video Call
    details: Manages the integration with a third-party WebRTC provider (e.g., Twilio, Vonage, Daily.co) to facilitate 1-on-1 video consultations. It handles session creation, token generation, and potentially basic session management
  - icon:
      src: /ORACLE.png
    title: Audit Logs
    details: A passive service dedicated to receiving and persistently storing audit events from all other microservices. This is crucial for compliance, security monitoring, and debugging, tracking critical actions, user access, and data modifications
---

