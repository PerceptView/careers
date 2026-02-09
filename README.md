# careers
---
### Company information

www.perceptview.com 

---

# Senior Software Developer  -- **POSITION FILLED** - we will post an update when new positions open later this year. 
### AwareView Command and Control Software System

PerceptView builds real-world, production systems for situational awareness, sensing, and data processing.

Our systems live at the intersection of hardware, software, networking, and reality where:

- **Latency matters**
- **At-a-glance comprehension saves lives**
- **Systems must recover from failures**
- **Private network operation is the norm** — not cloud-based services

**IMPORTANT NOTE**: This role may support federal contracts that require U.S. citizenship. Candidates must be eligible to work on such contracts when assigned. All applicants must be legally authorized to work in the United States; visa sponsorship is not available for this position.

| _posted: Dec 19, 2025_ | _expiry: NA_ | 

---

## THE ROLE

We are looking for a **Senior Software Engineer** who can design, build, and evolve complex systems with minimal supervision.

You will work across backend services, sensor and systems integrations, APIs, frontend components, and collaborate closely with a small team of developers.

You will work on **AwareView**, our in-house command and control software, to provide its operators awareness of the airspace our hardware is monitoring and protecting. This means ensuring sensor detections, video feeds, AI classifications, defeat resources, and other incoming information present a clear picture for operators under pressure to make rapid and accurate decisions.

This is **not** a “feature factory” role. This is a role for a senior developer who wants to work in various parts of the stack, can see the big picture, make efficient and clever decisions, and execute.

You will work with — and be supported by — a Software Architect with decades of experience and a penchant for thoughtful, robust, and maintainable code with quality error handling. Your documentation has (and will) evolve beyond “the code is the documentation” as you help your whole team and AwareView’s operators understand what you have created.

Your manager focuses on getting you what you need, asking clarifying questions, organizing priorities clearly, protecting your time, and getting out of your way.

**Work details:**
- **Location:** On-site strongly preferred; remote possible
- **Work week:** Monday–Friday, 40 hours, Mountain Time
- **Travel:** Likely, but occasional
- **Type:** Full-time employee or part-time contract

---

## WHAT YOU WILL DO

**Primary:** Software development for **AwareView**, our Command and Control software.

- Design and implement robust, production-grade systems with a clear understanding of trade-offs
- Take a big-picture view of system architecture and break it into executable plans
- Make technical decisions independently and explain them clearly
- Build systems that handle:
  - High I/O
  - Streaming data
  - Concurrent workloads
  - Offline (private network) operation
- Distinguish when code should be **parallel** vs **asynchronous**, and why
- Design for failure:
  - Log *why* something failed
  - Recover immediately when possible
  - Avoid brittle, cascading failure modes
- Integrate with third-party hardware, drivers, and lower-level system components
- Design, implement, and maintain REST APIs:
  - OpenAPI specifications
  - JSON Schema–driven validation
- Participate actively in technical discussions — asking questions early
- Occasionally work on frontend components (**Svelte 5**) without being expected to be a frontend specialist

You will be working on systems designed to save lives in the real world, in real time.  
This is **not** big tech.  
It **is** defense work.

---

## REQUIRED SKILLS

### Core Engineering
- Strong experience building **systems**, not just features
- Solid understanding of:
  - Concurrency models
  - Message passing (brokered or direct)
  - Stream-based processing
  - Failure modes and resiliency patterns
- Experience with offline or intermittently connected systems (strong plus)
- Comfort integrating across system boundaries (services, drivers, HALs, external systems)

### Languages & Platforms
- **Go** (primary language)
- **Python** (strong working knowledge)
- **JavaScript / TypeScript**
- **C** (bonus, not required)
- Strong Linux experience (development and deployment)

### APIs & Schemas
- REST API design and implementation
- OpenAPI (Swagger)
- JSON Schema
- CUElang experience (bonus)

### Frontend (Secondary)
- Some frontend development experience
- Willingness to work in **Svelte 5**
- Not required to be a frontend specialist

### Administration / Tools
- GitHub
- Scrum / Kanban hybrid
- Google Workspace
- Linux (very rare Windows interactions)

---

## HOW YOU WORK

This role is a good fit if you:

- Are comfortable working with ambiguity
- Don’t wait for perfect information
- Communicate proactively
- Take responsibility for outcomes, not just code
- Prefer systems that fail loudly, log clearly, and recover fast
- Build for the future without chasing perfection
- Enjoy high trust, real challenges, and occasional nerd jokes

This role is **not** a good fit if you:

- Need constant direction
- Avoid cross-cutting system concerns
- Only want frontend or isolated backend work
- Get stuck when answers aren’t immediately available
- Only want to write “perfect” code
- Prefer lots of meetings
- Think testing is for “other people”

---

## BENEFITS

- 401(k)
- 401(k) matching
- Health insurance
- Dental insurance
- Vision insurance
- Flexible schedule
- Paid time off

---

## MISC

- This role includes on-site work and may occasionally require the ability to lift, carry, and transport equipment weighing up to 50 pounds, for single person carry, or more (e.g., Pelican cases containing hardware and networking equipment). Reasonable accommodations may be provided in accordance with applicable law.

- This role may support federal contracts that require U.S. citizenship. Candidates must be eligible to work on such contracts when assigned. All applicants must be legally authorized to work in the United States; visa sponsorship is not available for this position.

- Employment with the company is contingent upon successful completion of a background check and, where applicable, a pre-employment drug screening.

- Candidates must possess a valid, state-issued form of identification and be able to verify employment eligibility in the United States.

- We are an equal opportunity employer and do not discriminate based on race, color, religion, sex, national origin, age, disability, veteran status, or any other protected characteristic under applicable law.

---

## How to Apply — Human-First Instructions

We review thoughtful submissions manually — not bots, not keyword clumps.

Please send the following to **apply@perceptview.com**:

1. **Your résumé / CV**
2. A **short paragraph (3–6 sentences)** describing a **software system you built that did *not* work as expected** — what happened and what you learned.
3. Include **exactly this phrase** in your email subject line:
PV-GH-Senior-SW-Dev
> This helps us route applications correctly and ensures your email is seen.

---

### Optional Bonus (Not Required)

If you’d like to stand out, you may optionally include one or more of the following:

- A short paragraph describing a technical decision you *disagreed* with — and how you handled it
- A link to something you’ve written or built (public or private is fine)
- A brief note explaining what part of PerceptView’s work *most* interested you — or what gave you pause

This section is entirely optional.

---

---

# What AwareView Is

AwareView is a multi-sensor situational awareness platform designed to detect, track, and monitor aircraft, drones (UAS/UAVs), and other airborne objects in real time. It integrates data from multiple hardware sources into a unified map-based interface that operators can monitor and act upon. Its strengths and versatility lies in:

- It is specifically designed as a sensor-agnostic, vendor-neutral, platform. Its integrations evolve with the sensing industry 

- Function over form: It follows a "Make it work first - make it pretty later" ethos. This is both for ensureing it works properly over any 'cool factor' and to keep the visual clutter / operator overhead as low as possible. Which isn't to say there is no room for serious graphical exploration and experimentation. 

- This is not our first rodeo with Counter UAS control software - a lot has been learned...plenty of live saving fun work still up for grabs

AwareView is specifically designed to function on private secured networks with no outside network connection which is often a requirement from our clients for security purposes. It certainly can connec to systems over public networks but it is not required and the least prefered use case. 

---

## What Users Actually Do with AwareView

### 1. Real-Time Monitoring & Visualization

Users access a browser-based map interface that displays:

- Live tracks of detected aircraft / airborne objects and drones with their positions, altitudes, and headings
- Detection classifications showing whether targets are likely UAS/drones, aircraft, or other objects
- Confidence probabilities for each classification
- A list of active tracks that can be selected for detailed information and actions

---

### 2. Hardware Integration & Configuration

Users configure and manage multiple sensor sources (“components”) that feed detection data into the system.

#### Ingress Sources (Input Devices)

- **Radar systems:** 
- **ADS-B receivers:** 
- **Drone detection systems:**  
- **Video tracking:**  
- **Network integration:**  
  Cursor on Target (CoT) for military/emergency coordination  
  WebSocket connections for inter-system communication

#### Egress Outputs (Data Export)

- Send filtered or transformed detection data to other systems via:
  - Cursor on Target (CoT) XML format over UDP/TCP
  - File system storage 
  - Other AwareView instances for distributed deployments

---

### 3. Geospatial Zone Management

Users define and enable detection zones to monitor, such as:

- **Circular zones:** Radius and altitude boundaries
- **Polygon zones:** Geographic boundaries with minimum and maximum altitude
- Zones can be **static** or **dynamic** (tied to a mobile platform or fixture)

---

### 4. Mission Planning & Tracking Tasks

Users create and manage tasks associated with components, such as:

- **Slew-to-cue tasks:** Automatically orient cameras or radars to detected targets
- **Zone monitoring tasks:** Trigger actions when targets enter or exit zones
- Tasks can be scheduled with configurable start and end times and enabled or disabled as needed

---

### 5. Hardware Management

Users configure the physical sensors and devices, for instance:

- Add ingress fixtures (radar systems, ADS-B receivers, drone detectors)
- Add egress fixtures (output channels to other systems)
- Define static location points (latitude, longitude, altitude) where sensors are positioned

---

### 6. System Administration

General system admininstration may include: 

- User authentication and access control
- Dark mode support for operator comfort during long shifts
- API access for automated integration
- Administrative panel for system configuration

---

## Key Problems AwareView Solves

- **Multi-source data visualization:** Combines radar, ADS-B, and RF-based detection into a single operational view
- **Real-time threat detection:** Identifies and tracks unauthorized aircraft and drones
- **Geospatial alerting:** Monitors defined zones and triggers responses when targets enter restricted airspace
- **System interoperability:** Works with military (CoT), civilian (ADS-B), and commercial detection systems
- **Automation:** Automatically orients cameras and sensors via slew-to-cue functionality
- **Distributed deployment / Federation:** Supports connecting multiple AwareView instances for wide-area coverage

---

## Target Use Cases

- Airport and airfield security
- Military airspace monitoring
- Critical infrastructure protection (power plants, government facilities)
- Emergency response and airspace coordination
- Border security and counter-UAS operations
- Wildfire monitoring via aircraft tracking

---

## System Architecture

AwareView is built as a microservices-like system using:

- PostgreSQL with PostGIS for geospatial data
- A web-based operator interface
- Go-based data processing services
- Python hardware drivers (currently being ported to Go)

The system is deployed on Rocky Linux / RHEL 9. It is not a web-based service. 

---

## Notes

This repository exists solely for hiring and career communication.  
It contains no source code or internal materials.


© PerceptView — All rights reserved.
