# Awesome-Remote-Patient-Monitoring

Edit
Top Remote Patient Monitoring (RPM) Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Remote Patient Monitoring, Connected Medical Devices, Chronic Care Management & Virtual Care
Last updated: August 2026

This repository tracks notable SaaS/Hosted platforms and open-source projects for Remote Patient Monitoring (RPM). These tools collect and analyze patient-generated health data from connected devices such as blood-pressure monitors, glucose meters, pulse oximeters, weight scales, ECG devices, wearables, and other medical sensors, then provide clinical dashboards, alerts, care workflows, patient engagement, and EHR integration.

Examples include Validic, Health Recovery Solutions, Optimize Health, Current Health, CareSimple, Biofourmis, CoachCare, Prevounce, Withings Health Solutions, 100Plus, Cadence, and Philips eCareCoordinator. Validic, for example, provides a device/data normalization layer with 700+ device integrations and real-time clinical alerts, while Prevounce combines RPM with broader remote-care management workflows.

Open-source emphasis: The open-source RPM ecosystem is smaller than the commercial ecosystem, but there are useful projects around telehealth, connected medical devices, vital-sign monitoring, FHIR/EHR interoperability, IoT, patient dashboards, and remote-care infrastructure. Projects such as MediPi and HomeICU provide particularly relevant foundations for experimentation and custom RPM deployments.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

Additional Strong Open-Source Options

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Validic
Enterprise remote-care and health-data infrastructure platform that normalizes data from hundreds of connected devices and integrates patient-generated health data into clinical workflows and EHRs.

Health Recovery Solutions
Remote patient monitoring and care-management platform supporting connected devices, patient engagement, clinical monitoring, care pathways, and transitional care.

Optimize Health
RPM platform designed to help healthcare organizations enroll patients, collect connected-device data, monitor populations, and manage chronic conditions remotely.

Current Health
Enterprise hospital-to-home platform combining remote monitoring, connected medical devices, patient data, and clinical workflows.

CareSimple
Remote patient monitoring platform supporting connected medical devices, patient engagement, clinical monitoring, and chronic-care workflows.

Biofourmis
Digital health platform using continuous patient data, wearable sensors, analytics, and AI-driven insights for remote monitoring and personalized care.

CoachCare
Connected-care and RPM platform combining remote monitoring devices, patient engagement, coaching, care management, and clinical dashboards.

Prevounce
Cloud-based remote-care management platform supporting RPM, chronic care management, advanced primary care management, and annual wellness programs, with connected devices and workflow automation.

Withings Health Solutions
Connected-health ecosystem providing medical-grade connected devices and APIs for integrating weight, blood pressure, ECG, activity, and other patient-generated health data into healthcare workflows.

100Plus
Remote-care platform combining RPM and chronic-care management with cellular-connected devices, monitoring, alerts, patient engagement, EHR integration, and reimbursement support.

Cadence
Technology-enabled chronic-care platform combining connected devices, continuous monitoring, clinical teams, and personalized care programs.

Philips eCareCoordinator
Remote-care and telehealth technology supporting clinical monitoring, care coordination, patient data, alerts, and virtual-care workflows.

CareSimple
Connected RPM platform providing device-based monitoring, patient engagement, clinical workflows, and population management.

Vivify Health
Digital care platform supporting remote monitoring, virtual care, chronic-care management, patient engagement, and hospital-to-home programs.

Teladoc Health Chronic Care
Connected-health and chronic-condition management ecosystem supporting remote monitoring, digital therapeutics, coaching, and virtual care.

Huma
Digital health platform providing remote monitoring, patient engagement, clinical workflows, and disease-specific digital care pathways.

TytoCare
Remote examination and connected-care platform enabling clinicians to conduct guided examinations and collect clinical measurements remotely.

Medically Home
Technology-enabled hospital-at-home ecosystem supporting remote patient care, monitoring, clinical coordination, and acute-care-at-home models.

Aiva Health
Voice-enabled and connected-care technology supporting remote communication, monitoring, and patient engagement in healthcare environments.

Luscii
Virtual-care and remote-monitoring platform supporting chronic disease management, connected devices, patient questionnaires, alerts, and clinical workflows.

Datos Health
No-code remote-care platform for building personalized digital care pathways and integrating patient-generated health data into clinical workflows.

Tunstall Healthcare
Connected health and telecare ecosystem providing remote monitoring, safety, communication, and assisted-living technologies.

Care Innovations
Digital health technology supporting remote monitoring, care management, and connected patient-care programs.

eClinicalWorks healow
Patient-facing digital health ecosystem supporting remote monitoring, patient engagement, telehealth, and connected healthcare workflows.

Validic Inform
Health-data infrastructure layer for ingesting and normalizing data from connected devices and health applications before delivery into healthcare systems.

RPM platforms generally span several overlapping capabilities: device connectivity, patient onboarding, physiologic-data ingestion, clinical dashboards, threshold alerts, care management, patient engagement, EHR integration, reimbursement workflows, and population health analytics.

Open-Source GitHub Projects

MediPi
Open-source NHS-originated telehealth and remote patient monitoring platform designed to transmit measurements from patient environments to remote clinicians. It supports measurements including blood pressure, oxygen saturation, weight, and patient questionnaires, with extensible device connectivity.

HomeICU
Open-source remote patient monitoring project using wearable sensors and a remote monitoring architecture for collecting vital signs and enabling clinicians to monitor patients remotely.

HealthConnect
Open-source medical IoT application designed to connect devices such as ESP32/ESP8266 boards, Raspberry Pi systems, and smartphones to a cloud-based patient health dashboard with real-time sensor data.

AIOTP — All in One Telehealth Platform
Open-source telehealth suite combining OpenEMR-based clinical records with Jitsi-based videoconferencing and FHIR integration components. Useful as a broader telehealth foundation around an RPM system.

OpenEMR
Open-source electronic health-record and practice-management platform that can serve as the clinical-system foundation for custom RPM integrations.

OpenMRS
Open-source medical-record platform suitable as a backend clinical system for custom remote-monitoring and patient-data workflows.

GNU Health
Open-source health information system that can provide a broader clinical-data foundation for custom RPM implementations.

FHIR
Open healthcare interoperability ecosystem that provides the standards and implementation resources needed to represent and exchange observations, devices, patients, care plans, and clinical data generated by RPM systems.

Additional Strong Open-Source Options

HAPI FHIR for implementing FHIR servers and healthcare-data interoperability layers.

Medplum for building developer-oriented, FHIR-native healthcare applications and patient-data workflows.

OpenTelemetry for observability of distributed RPM applications and device-data pipelines.

Eclipse Mosquitto for lightweight MQTT-based medical IoT and connected-device messaging.

Node-RED for connecting medical devices, APIs, MQTT streams, databases, alerts, and custom RPM workflows.

Apache Kafka for streaming high-volume physiologic measurements and device events.

Apache Flink for real-time processing of patient telemetry and alerting pipelines.

Grafana for building real-time patient-monitoring and operational dashboards.

PostgreSQL for storing structured patient, device, measurement, and care-management data.

TimescaleDB for time-series storage and analysis of continuous physiologic measurements.

ThingsBoard for IoT device management, telemetry ingestion, dashboards, and rule-based processing.

OpenRemote for open-source IoT device management and automation that can be adapted for connected-health environments.

Jitsi Meet for integrating secure video consultations into custom RPM/telehealth systems.

Keycloak for identity, authentication, authorization, and single-sign-on infrastructure.

MinIO for self-hosted object storage for medical-device data, reports, and clinical artifacts.

Apache Superset for population-level RPM analytics and operational reporting.

Framework for building a custom open-source RPM platform: Combine MediPi/HomeICU for device-to-clinician monitoring concepts; FHIR + HAPI FHIR/Medplum for interoperability; OpenEMR/OpenMRS/GNU Health for clinical workflows; MQTT + Mosquitto + Node-RED for device connectivity; Kafka/Flink for streaming analytics; PostgreSQL/TimescaleDB for patient telemetry; and Grafana for real-time dashboards.

The commercial ecosystem remains substantially more mature for enterprise device logistics, clinical operations, reimbursement, regulatory compliance, EHR integration, and large-scale RPM deployment. The open-source ecosystem is better viewed as a collection of building blocks and reference implementations rather than a set of turnkey replacements for enterprise RPM vendors. MediPi, for example, explicitly provides patient software, server-side components, APIs, and support for multiple types of measurements and device interfaces.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

For open-source projects, preferably include the GitHub repository and license.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Some open-source projects listed here are building blocks rather than direct replacements for commercial RPM platforms.

Always verify the current license, maintenance activity, security posture, regulatory status, and production suitability before deployment.

Remote patient monitoring can involve clinical and safety-critical data. Open-source software should not be treated as medically validated or clinically certified merely because it is open source.

Appropriate HIPAA, GDPR, FDA/medical-device, cybersecurity, privacy, interoperability, and local healthcare requirements should be evaluated before using any system with real patients.

Device accuracy, clinical validation, data integrity, alerting reliability, and secure handling of patient information require appropriate healthcare-grade engineering and validation.

Made for healthcare providers, hospitals, digital-health companies, RPM program operators, researchers, developers, and healthcare technologists.
Let's make remote patient monitoring more open, interoperable, data-driven, and accessible.
