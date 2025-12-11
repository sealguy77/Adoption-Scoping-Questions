# Adoption & Change Management Scoping Assistant

## Purpose

This AI-powered scoping assistant helps change management professionals conduct structured, evidence-based readiness assessments during customer discovery conversations. Optimized for use with advanced AI assistants like GitHub Copilot, ChatGPT, or Claude, it provides real-time analysis, identifies gaps, and generates strategic recommendations grounded in industry-standard change management frameworks.

---

## Key Features

✅ **Structured 10-Dimension Assessment** - Comprehensive evaluation across critical adoption factors  
✅ **Real-Time AI Guidance** - Section-by-section analysis with gap identification and probing questions  
✅ **Industry Frameworks Integrated** - Prosci, Kirkpatrick, Competing Values, Schein, Risk Analysis, and more  
✅ **Role-Based Perspective Analysis** - Accounts for information source bias and blind spots  
✅ **Evidence-Based Recommendations** - Strategic action plans with priorities, owners, and timelines  
✅ **Professional Deliverables** - Executive summary, scorecard, risk matrix, resource requirements  

---

## How It Works

### 1. **Prepare for Your Customer Meeting**
- Copy the entire prompt from `Adoption_Scoping_Prompt.md` (from "# Adoption & Change Management Scoping Assistant" to "# PROMPT END")
- Paste it into your preferred AI assistant (GitHub Copilot Chat, ChatGPT, Claude, etc.)
- Have the AI window open alongside your customer meeting

### 2. **Initial Context Gathering**
The AI will first ask you to provide:
- Customer profile (company, industry, size)
- Contact information (name, role, department)
- Their project role (sponsor, PM, stakeholder, etc.)
- Conversation purpose (discovery, validation, planning)

**Critical Enhancement:** The AI uses a role-based perspective bias table to account for potential blind spots based on who you're speaking with (Executive vs. PM vs. IT Lead vs. Change Manager).

### 3. **Guided Section-by-Section Assessment**
The AI walks you through 10 critical dimensions, providing:

| Section | Focus Area | Analysis Framework |
|---------|-----------|-------------------|
| **1. Project & Change Scope** | Change type, impact footprint, timeline | Scope clarity, timeline realism, value proposition |
| **2. Executive Sponsorship** | Sponsor quality, commitment, resources | Prosci Sponsorship Model (5 actions) |
| **3. Change Capacity** | Change history, saturation, attitude | Change Saturation Risk Model |
| **4. Stakeholder Engagement** | Mapping, resistance, communication | Power-Interest Matrix, Engagement Maturity |
| **5. Change Management Capabilities** | Expertise, planning, methodology | Change Management Maturity Model (5 levels) |
| **6. Training & Enablement** | Needs analysis, delivery, proficiency | Kirkpatrick's Four Levels of Evaluation |
| **7. Communication Strategy** | Planning, channels, storytelling | Effective Communication Principles |
| **8. Cultural Context** | Culture type, trust, psychological safety | Competing Values Framework, Schein's Model |
| **9. Success Metrics** | KPIs, baselines, targets, interventions | Adoption Metrics Hierarchy (4 levels) |
| **10. Risk Assessment** | Risk ID, mitigation, contingency | Risk Impact/Probability Matrix |

### 4. **Interactive Analysis Per Section**
After you share customer responses for each section, the AI provides:

- ✅ **Strengths** - Positive readiness indicators identified
- ⚠️ **Gaps & Risks** - Concerns, red flags, missing foundations
- 🔍 **Ambiguities** - Vague information requiring clarification
- 📊 **Evidence Needs** - Specific data points to validate claims
- 🔎 **Follow-Up Questions** - Diplomatic probing suggestions to fill gaps
- 📝 **Section Summary** - Key findings before moving forward

### 5. **Comprehensive Final Assessment**
After all 10 sections, receive a strategic deliverable including:

#### **Executive Summary Scorecard**
- Evidence-based scoring (🟢 High / 🟡 Medium / 🔴 Low) for each dimension
- Risk levels (🟢 Low / 🟡 Moderate / 🔴 High)
- Key evidence from the conversation
- Primary gaps or concerns

#### **Strategic Go/No-Go Recommendation**
- **🟢 Ready to Proceed** - 7+ high scores, no showstoppers, clear path forward
- **🟡 Proceed with Caution** - 4-6 high scores, addressable gaps, risk mitigation required
- **🔴 Not Ready** - <4 high scores, critical showstoppers, foundation-building needed

#### **Actionable Deliverables**
1. **Critical Success Factors** - Top 3-5 make-or-break factors
2. **Prioritized Action Plan** - Critical, 30-day, 60-90 day, and ongoing actions
3. **Top 5 Risks & Mitigation** - Specific risks with owners and mitigation strategies
4. **Resource Requirements** - Roles, FTEs, budget estimates, leadership time
5. **Critical Conversations** - Decisions requiring executive attention
6. **Red Flags & Showstoppers** - Deal-breakers explicitly called out
7. **Information Gaps** - Missing critical information documented
8. **30-Day Roadmap** - Week-by-week action plan with owners
9. **90-Day Success Indicators** - What "good" looks like

---

## What Makes This Approach Effective

### **Industry-Standard Frameworks**
The prompt integrates proven change management methodologies:
- **Prosci ADKAR & Sponsorship Model** - Industry standard for change management
- **Kirkpatrick's Four Levels** - Training evaluation best practice
- **Competing Values Framework** - Organizational culture assessment
- **Schein's Three Levels of Culture** - Deep cultural analysis
- **Power-Interest Matrix** - Stakeholder management
- **Change Management Maturity Model** - Capability assessment
- **Risk Impact/Probability Matrix** - Risk prioritization

### **Role-Aware Analysis**
The AI adjusts its analysis based on who you're speaking with:

| Contact Role | Typical Strengths | Common Blind Spots | AI Probing Focus |
|--------------|-------------------|--------------------|--------------------|
| **Executive Sponsor** | Strategic vision, business case | Operational details, resistance patterns | Ground-level impact, middle management |
| **Project Manager** | Timelines, deliverables | Cultural dynamics, emotional resistance | Stakeholder sentiment, change history |
| **IT Leadership** | Technical feasibility | User experience, behavioral complexity | Actual workflows, training effectiveness |
| **HR/Change Manager** | People dynamics, culture | Technical constraints | Technical dependencies, timeline |
| **End-User Rep** | Ground-level reality | Strategic context | Executive commitment, resources |

### **Evidence-Based Approach**
Every finding is linked to specific conversation details, not assumptions. The AI is instructed to:
- Quote specific customer statements
- Identify patterns across sections
- Test assumptions with probing questions
- Validate vague claims with follow-ups
- Connect tactical gaps to strategic impact

---

## Tips for Effective Use

### **Before the Meeting**
- [ ] Copy the prompt into your AI assistant
- [ ] Position AI window on a second screen or alongside meeting window
- [ ] Brief the customer that you'll be taking comprehensive notes
- [ ] Review the 10 assessment dimensions to familiarize yourself

### **During the Meeting**
✅ **Ask questions conversationally** - Don't read verbatim from the prompt; make it natural  
✅ **Copy-paste or paraphrase** customer responses into the AI  
✅ **Review AI analysis briefly** between sections (30-60 seconds)  
✅ **Weave in follow-up questions** naturally when the AI suggests them  
✅ **Use bridging phrases:** "That's helpful—can you tell me more about..." or "Help me understand..."  
✅ **Don't rush** - Depth is more valuable than speed  

### **Managing the Conversation**
- **If customer doesn't know:** Note the gap; AI will flag it as a risk
- **If customer is vague:** AI will generate specific probing questions
- **If customer is overly optimistic:** AI will suggest reality-checking questions
- **If running short on time:** Ask AI which sections are most critical given what you've learned
- **If customer goes off-topic:** Capture useful info, then gently redirect to framework

### **After Each Section**
1. Briefly review AI's analysis (✅ strengths, ⚠️ gaps, 🔍 follow-ups)
2. Ask critical clarifying questions before moving on
3. Summarize back to customer: "Let me make sure I captured that correctly..."
4. Confirm readiness to proceed to next section

### **Post-Meeting**
- Copy the full AI assessment into your notes/CRM
- Use the deliverables for proposals, SOWs, or project plans
- Schedule follow-up conversations to fill critical information gaps
- Share appropriate sections with customer stakeholders

---

## Common Use Cases

### **Scenario 1: Early Discovery**
- **Stage:** Initial customer conversation about potential project
- **Goal:** Determine if they're ready to invest in adoption and change management
- **Output:** Go/no-go recommendation with resource and timeline estimates

### **Scenario 2: Proposal Development**
- **Stage:** Responding to RFP or creating custom proposal
- **Goal:** Identify scope, risks, and resource requirements
- **Output:** Comprehensive assessment to inform proposal pricing and approach

### **Scenario 3: Project Kickoff**
- **Stage:** Project has been approved; planning phase
- **Goal:** Baseline assessment to inform change management strategy
- **Output:** Detailed action plan, resource plan, and risk mitigation strategy

### **Scenario 4: Mid-Project Assessment**
- **Stage:** Project is in flight; checking readiness before major milestone
- **Goal:** Identify emerging risks and course-correct
- **Output:** Updated assessment with interventions and adjustments

### **Scenario 5: Vendor Selection**
- **Stage:** Customer evaluating change management support options
- **Goal:** Demonstrate structured, professional approach
- **Output:** Comprehensive readiness assessment showcasing expertise

---

## Example Conversation Flow

```
You: [Paste prompt into Copilot Chat]

Copilot: I'm ready to guide you through this adoption and change management 
         scoping conversation. Before we begin the assessment, let me gather 
         some foundational context:
         
         1. Organization: Company name, industry sector, size?
         2. Contact Information: Name, title, department, tenure?
         3. Project Role: Executive sponsor, project lead, stakeholder, or other?
         4. Conversation Purpose: Discovery, validation, planning, or other?

You: Contoso Manufacturing, 5000 employees, healthcare equipment sector.
     Speaking with Jane Smith, VP of IT, 8 years with company.
     She's the executive sponsor for a Microsoft 365 Copilot rollout.
     This is early discovery to scope change management needs.

Copilot: Perfect. Since Jane is the executive sponsor and VP of IT, I'll pay 
         special attention to:
         - Change management capabilities (she may underestimate complexity)
         - End-user readiness and resistance patterns (potential blind spot)
         - Cultural and behavioral factors (may not be top of mind)
         - Training effectiveness (technical focus vs. adoption focus)
         
         Let's begin with Section 1: Project & Change Scope.
         
         **Core Discovery Questions:**
         1. What is the fundamental nature of this change?
         2. Which user groups are affected and how many users per segment?
         3. What specific behaviors must change?
         4. What is the planned rollout schedule?
         5. What's the value proposition for end-users?
         
         Share what the customer tells you about these areas.

You: [Shares customer responses about aggressive 3-month timeline, 
     all 5000 users at once, no pilot planned, driven by CEO mandate]

Copilot: **Analysis - Section 1: Project & Change Scope**
         
         ✅ Strengths:
         - Clear executive mandate provides urgency
         - Organization-wide scope shows strategic importance
         
         ⚠️ Gaps & Risks:
         - 🚨 RED FLAG: 3-month timeline for 5000 users is extremely aggressive
         - 🚨 RED FLAG: No pilot = no opportunity to learn and adjust
         - CEO mandate may indicate top-down push without user input
         - No mention of user value proposition or "WIIFM"
         
         🔍 Ambiguities Requiring Clarification:
         - What's driving the 3-month timeline? (business need vs. arbitrary)
         - How disruptive will this be to daily work? (scale 1-10)
         - What familiar tools/processes will users abandon?
         - Have users been consulted or informed?
         
         📊 Evidence Needed:
         - Current tool usage patterns (baseline)
         - User sentiment about current tools
         - Role-specific impact analysis
         
         **Suggested Follow-Up Questions:**
         1. "Help me understand what's driving the 3-month timeline—is there 
            a business imperative or contract deadline?"
         2. "On a scale of 1-10, how disruptive will this be to daily work? 
            What makes you rate it that way?"
         3. "What's the compelling reason for end-users to adopt this? What 
            problem does it solve for them?"
         4. "Has there been any discussion of a pilot with a smaller group first?"
         
         Please ask these and share additional responses before we proceed to 
         Section 2.

You: [Continues conversation through all 10 sections...]

Copilot: [After Section 10, provides comprehensive final assessment with 
         scorecard, strategic recommendation, action plan, risks, resources, 
         and next steps]
```

---

## Requirements

- **AI Assistant:** GitHub Copilot Chat, ChatGPT (Plus or Enterprise), Claude (Pro), or similar
- **File:** `Adoption_Scoping_Prompt.md` from this repository
- **Meeting Context:** Live customer conversation, recorded interview, or asynchronous Q&A

---

## Files in This Repository

- **`README.md`** (this file) - Complete usage guide and methodology
- **`Adoption_Scoping_Prompt.md`** - The full AI assistant prompt (copy and paste into your AI tool)

---

## Best Practices for Change Management Professionals

1. **Start with context** - Always provide complete customer and contact information to the AI
2. **Trust the frameworks** - The integrated models are industry-proven; let them guide you
3. **Probe with curiosity** - Use AI-suggested questions to uncover hidden issues diplomatically
4. **Document as you go** - Save AI analysis in real-time to your notes/CRM
5. **Be honest about gaps** - Better to identify issues in discovery than at launch
6. **Use perspective accounting** - Remember the AI adjusts for the role of your information source
7. **Follow up systematically** - Address critical information gaps before finalizing recommendations
8. **Leverage deliverables** - Use AI output for proposals, project charters, and executive briefings
9. **Iterate and refine** - If recommendations aren't practical, share constraints and ask for alternatives
10. **Build your library** - Save successful assessments as templates and examples

---

## Why This Approach Works

### **Comprehensive Yet Practical**
Covers all critical dimensions without overwhelming the conversation. The structured approach ensures nothing is missed while remaining flexible to customer needs.

### **Grounded in Research & Practice**
Every framework, model, and assessment criterion comes from established change management literature and proven methodologies (Prosci, Kotter, Kirkpatrick, Schein, etc.).

### **Real-Time Intelligence**
Unlike post-meeting analysis, you get immediate insights and follow-up questions while you can still probe deeper—dramatically improving assessment quality.

### **Role-Aware & Bias-Conscious**
Explicitly accounts for perspective bias based on who you're speaking with, ensuring you probe for information in their blind spots.

### **Evidence-Based & Specific**
Every finding is tied to actual conversation details, not generic assessments. Recommendations include owners, timelines, and success criteria.

### **Professional Deliverables**
Output is client-ready: executive summaries, scorecards, risk matrices, action plans, and resource estimates that can be directly incorporated into proposals and project plans.

---

## Contributing

Have suggestions for improving the framework or assessment methodology? Encountered a scenario not well-addressed by the current approach? Please submit issues or pull requests.

---

## License

This project is provided as-is for use in customer scoping and discovery conversations for adoption and change management initiatives.

---

## About

This scoping assistant was designed for change management professionals working on digital transformation, technology adoption, process improvement, and organizational change initiatives. It's particularly valuable for consultants, internal change managers, and project leaders who need to quickly and comprehensively assess readiness and develop evidence-based recommendations.
