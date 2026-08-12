---
enable: true

heading: "Heating & Cooling Services in Boston, MA"
description: "Get help with HVAC repairs, installation, maintenance, and indoor air quality for your Boston-area home."

# Pexels photo 32497161 by Kathleen Austin Kuhn. The image is decorative,
# so its accessible alternative is intentionally empty.
backgroundImage: "/images/alternative-hero-hvac.jpg"
backgroundImageAlt: ""

checklist:
  - "Air Conditioning Repair"
  - "Heating Repair"
  - "HVAC Installation & Replacement"
  - "Preventive Maintenance & Indoor Air Quality"

button:
  # Refer to sharedButton in src/sections.schema.ts for all options.
  enable: true
  label: "Contact Us"
  url: "/#alternative-hero-form"
  variant: "fill"
  rel: ""
  target: ""
  class: "px-8 py-4"
  icon:
    enable: false
    name: "ArrowUpRight"
    position: "right"

form:
  title: "Request Your Service"
  description: "Tell us what you need and we'll use your information to follow up about your request."
  emailSubject: "New HVAC service request"

  fields:
    firstNameLabel: "First Name"
    lastNameLabel: "Last Name"
    phoneLabel: "Phone Number"
    emailLabel: "Email"
    servicesLabel: "Which service do you need?"
    servicesPlaceholder: "Select one or more services"

  services:
    - "AC Repair"
    - "Heating Repair"
    - "HVAC Installation"
    - "Preventive Maintenance"
    - "Indoor Air Quality"
    - "Emergency HVAC Service"

  submitButton:
    # Refer to sharedButton in src/sections.schema.ts for all options.
    enable: true
    tag: "button"
    label: "Request Service"
    variant: "fill"
    rel: ""
    target: ""
    class: "px-8 py-4"
    icon:
      enable: false
      name: "ArrowUpRight"
      position: "right"

  messages:
    validation: "Please complete all required fields."
    servicesRequired: "Select at least one service."
    pending: "Submitting your service request..."
    success: "Thank you. Your service request has been received."
    error: "We couldn't submit your request. Please try again."
    unknownProvider: "The configured form provider is not available."
---
