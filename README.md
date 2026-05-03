# Development Note 
Winner at Luma A2A Agents Hackathon 2025. This project was built and launched in **under 12 hours**.


# Inspiration
Scheduling today is fragmented and frustrating. Whether it's setting up a haircut, finding a hackathon, or confirming a dentist appointment. We waste time looking up contacts, negotiating times, and making phone calls. We wanted to automate that entire workflow. SensePlan was inspired by the vision of an agentic AI secretary, one that doesn't just remind you of meetings, but actively plans your life, makes calls, negotiates on your behalf, and respects your personal rhythms and preferences. It's like having an executive assistant powered by LLMs and real-time APIs.

# What it does
SensePlan is an AI-powered personal assistant that helps users plan, schedule, and execute events and appointments so you never have to dial yourself. Key features: Natural Language Scheduling: Just say “schedule a haircut tomorrow” or “find me a hackathon next week.” Smart Calendar Management: Uses AI + your preferences to suggest the best time slots and syncs with Google Calendar AI-Powered Calls & Transcription: SensePlan makes the call, confirms appointments, and gives you a transcript Web Data Search: Finds contact info and event details in real-time using BrightData User Profile Memory: Remembers your work hours, breaks, preferences, and past interactions. Event Suggestions: Find fun or career-boosting events to enrich your schedule.

# How we built it
BrightData (Real-Time Data Sourcing) Find suggested events based on profile information Fetch barbershop numbers, hackathon links, Enrich vague requests like “find a coding event this weekend.” Vapi (AI Calling & Transcription) Place AI calls to confirm bookings. Capture multi-turn dialogue (e.g., “Can you do 2 PM instead?”). Transcribe conversations and auto-log them to the calendar. Arcade (Calendar Scheduling) Suggest optimal time slots based on your preferences. Add/update calendar events, manage conflicts. Decompute We attempted to make an ai agent that would specialize in seeing if we could summarize the Vapi Ai assistant transcript when creating appointments. We tried to use blackbird and decompute SDK and tried to build and deploy the ai agent.
