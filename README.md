# Study Space Finder @ NYU

A mobile web app that shows real-time, crowd-sourced availability and “fit” (noise level, outlets, group-friendliness) of study spaces across NYU so students can spend less time hunting and more time studying.

## What and why?

**Problem.** NYU students are spread across multiple buildings and neighborhoods, and quiet, available study seats are hard to find, especially around peak hours. Information about spaces (library floors, department lounges, pop-up study rooms, reservable rooms) is scattered across emails, PDFs, websites, and word-of-mouth. The university does not publish comprehensive, up-to-date availability for most spaces, so students waste time walking between locations only to find them full or unsuitable (too loud, no outlets, poor Wi-Fi).  

The challenge is not only for **individual quiet study**:  
- Students working on **group projects** often need larger desks or collaborative spaces where they can talk freely without disturbing others.  
- Commuter students, who may have **online classes back-to-back with in-person ones**, need reliable places with Wi-Fi and outlets to attend virtual lectures in between.  
- Sometimes students need the **fastest nearby spot for an urgent meeting or call**, where proximity matters more than amenities.  
- **Late-night availability** is a recurring challenge since some spaces close earlier than expected, leaving students stranded during evening study sessions.  
- **Overcrowding at peak times** (especially at Bobst Library) creates a significant need for alternative study spots, while other lesser-known but suitable spaces remain underused.  

**Solution.** **Study Space Finder** is a mobile web application that aggregates and **crowd-sources real-time occupancy and conditions** (quiet/noise, outlets, Wi-Fi, lighting, group-friendly) for study spots on and near campus. It surfaces the best options right now based on a student’s preferences and location, with lightweight check-ins and quick ratings to keep data fresh.

## For whom?

The NYU student body (undergraduates and graduate students who need quiet or collaborative spaces on short notice). Teaching assistants and small study groups who need reliable spots for collaborative work or tutoring.  

For example:  
- As a commuter student, I and many of my friends often have online classes back-to-back with in-person ones. We need dependable places with Wi-Fi and outlets to attend those classes and to work in between without rushing across campus.  
- My peers and I also need spaces for group study sessions between classes, where we can talk and collaborate without disturbing others.  
- In my role as a teaching assistant, I sometimes need to host online tutoring sessions, which requires a quiet space with stable internet and enough room to screen-share or work through problems with students.  

## How?

When a student opens **Study Space Finder** , they can:  
- **Browse or search nearby spaces** (libraries, lounges, classrooms, etc.) from a map view or a list view.  
- **See real-time availability** indicators like *Empty*, *Some seats*, or *Crowded*.  
- **Filter spaces by needs** such as quiet areas, group-friendly seating, outlets, strong Wi-Fi, or late-night hours.  
- **Check in** to update the status of a space for others, or confirm details like noise level or outlet availability.  
- **Save favorite spots** for quick access and reminders when they tend to be busy.  
- **Access reservation links** for spaces that require booking through NYU or campus authorities (for instance, Bobst study rooms), the app will provide direct links to the official reservation sites.  
- **View access rules**. Each space will clearly display restrictions such as graduate students only, specific departments such as CDS students only, or open to all.  


## Scope
Key features that require implementation include:  
- A mobile-friendly interface for browsing and filtering spaces.  
- A data model to store study spaces, check-ins, and access rules.  
- A check-in system that updates real-time availability and conditions.  
- Integration of reservation links for certain spaces.  
- Display of access restrictions (e.g., graduate-only, department-only). 

The work naturally divides across a team of 4 to 6 students: frontend UI/UX, backend services, database design, and user research/testing.   


