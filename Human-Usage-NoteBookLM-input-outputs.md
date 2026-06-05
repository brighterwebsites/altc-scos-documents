# ALTC FAST Track Generator - Library Index
**version** 2.0
**Last Updated**: December 16, 2024

## Purpose

This is your **Strategy and Framework Documentation Library** — the core framework artifacts that can be referenced to understand Authority-Led Topic Cluster (ALTC) Framework and other supporting concepts required to **implement ALTC Framework using the Fast Track methodology**.

---

## Document Architecture: Reference-Based Structure

This Claude Project uses a **reference-based architecture** to minimize duplication and maintenance overhead:

- **Framework Definitions** (SSOT) → Stored in brighter-frameworks-docs
- **Fast Track Application** → References definitions + adds operational process
- **Worked Examples** → Show complete implementation
- **Human Usage Guides** → User-facing instructions

When framework definitions change, only the SSOT documents need updating. Fast Track operational docs remain stable unless the PROCESS changes.

---

## Shared Documents (SSOT)

Key documents are shared between Framework development, Business Strategy Development, Content Creation and other AI tools and systems. This Library Index relies on the following shared documents from the "Single Source of Truth" (SSOT) stored on GitHub.

**SSOT Location:** brighter-frameworks-docs/

### **ALTC-Framework-Definitions.md** ⭐ CORE REFERENCE
**Path:** brighter-frameworks-docs/frameworks/ALTC-Framework-Definitions.md  
**Purpose:** Complete definitions of all framework components (WFB, ALTC, SLTC, Three Dimensions, Authority Anchors, Maturity Levels, Voice Gaps, etc.)  
**AI Usage:** Reference this for any framework concept definitions. This is the single source of truth.  
**Status:** v1.0 - Active SSOT

### **WFB-Blueprint-Overview.md**
**Path:** brighter-frameworks-docs/frameworks/WFB-Blueprint-Overview.md  
**Purpose:** Full Website-First Blueprint methodology - the container framework that ALTC lives within  
**AI Usage:** Understand how ALTC (Pillar 3) fits within overall WFB methodology  
**Status:** v1.0 - Active

### **Altc-origin-story-master.md**
**Path:** BW_WFB_Implementation/Altc-origin-story-master.md  
**Purpose:** Complete origin story - why ALTC was created, the emotional journey, validation  
**AI Usage:** Understand the "why" behind positioning-first approach and Fast Track philosophy  
**Status:** v1.0 - Active

### **Proprietary-Terminology-Reference.md**
**Path:** brighter-frameworks-docs/Proprietary-Terminology-Reference.md  
**Purpose:** Naming conventions, trademark status, and terminology consistency  
**AI Usage:** Use correct terminology when generating content  
**Status:** v1.0 - Active

### **GLOSSARY.md**
**Path:** brighter-frameworks-docs/GLOSSARY.md  
**Purpose:** Quick reference glossary of terms  
**AI Usage:** Quick lookup for term definitions  
**Status:** v1.0 - Active

---

## Fast Track Specific Documents

Documents specific to this Claude AI Co-Pilot for ALTC Fast Track implementation.

### **ALTC-Framework-Fasttrack.md** ⭐ PRIMARY OPERATIONAL GUIDE
**Path:** Claude-ALTC-Fasttrack/ALTC-Framework-Fasttrack.md  
**Purpose:** Operational guide for Fast Track Generator - HOW to analyze, WHAT to output, workflow process  
**Architecture:** References ALTC-Framework-Definitions.md for concepts, focuses on application  
**AI Usage:** This is your PRIMARY instruction document for generating Fast Track recommendations  
**Status:** v2.1 - Active (refactored to reference-based architecture Dec 16, 2024)  
**Lines:** ~410 (reduced from 666 by eliminating duplication)

### **Claude-Instructions.md**
**Path:** Claude-ALTC-Fasttrack/Claude-Instructions.md  
**Purpose:** Detailed operational instructions, interaction protocols, output formatting  
**AI Usage:** Supplementary to ALTC-Framework-Fasttrack.md - detailed execution guidance  
**Status:** v1.0 - Active  
**Note:** May need review for consistency with v2.1 of Framework-Fasttrack document

### **ALTC_Fast_Track_Worked_Example.md** ⭐ REFERENCE EXAMPLE
**Path:** Claude-ALTC-Fasttrack/ALTC_Fast_Track_Worked_Example.md  
**Purpose:** Complete worked example for Regional Electrical Services business showing full Fast Track output  
**AI Usage:** Reference for output format, structure, level of detail, and strategic reasoning  
**Status:** v1.0 - Active

### **Voice-Guide-Generator-for-ALTC-Content-Engine.md**
**Path:** Claude-ALTC-Fasttrack/Voice-Guide-Generator-for-ALTC-Content-Engine.md  
**Purpose:** Brand Voice Guide Generator for ALTC Content Writing, supports rapid authority positioning  
**AI Usage:** Optional tool for analyzing brand voice when needed for content recommendations  
**Status:** v1.0 - Active

---

## Human Usage Guides

Documents specific to this AI Co-Pilot for human users - instructions, cross-platform prompts, input preparation.

**Note:** AI should reference these when user mentions input preparation or process questions.

### **Human-Usage-NoteBookLM-input-outputs.md**
**Path:** Claude-ALTC-Fasttrack/Human-Usage-NoteBookLM-input-outputs.md  
**Purpose:** The 17 strategic questions for NotebookLM business intelligence extraction  
**User Action:** Copy questions → Paste into NotebookLM → Provide output to Claude  
**Status:** v1.0 - Active

### **Human_Usage Guide_ALTC_Inputs.md**
**Path:** Claude-ALTC-Fasttrack/Human_Usage Guide_ALTC_Inputs.md  
**Purpose:** Input preparation guide for users (currently empty - needs development)  
**Status:** Draft/Placeholder

### **Human_Usage_Guide_BrandVoice.md**
**Path:** Claude-ALTC-Fasttrack/Human_Usage_Guide_BrandVoice.md  
**Purpose:** Brand voice extraction process for users  
**Status:** v1.0 - Active

---

## Archived/Superseded Documents

### **ALTC-Framework-Overview-fork-1.md** ❌ SUPERSEDED
**Status:** Archived - content integrated into ALTC-Framework-Definitions.md  
**Note:** Can be deleted or archived. No longer referenced.

### **ALTC-Framework-Overview-fork-2.md** ❌ SUPERSEDED
**Status:** Archived - content integrated into ALTC-Framework-Definitions.md  
**Note:** Can be deleted or archived. No longer referenced.

---

## Document Update Protocol

### When Framework Concepts Change
**Update:** ALTC-Framework-Definitions.md (SSOT)  
**No update needed:** ALTC-Framework-Fasttrack.md (references definitions)

### When Fast Track Process Changes
**Update:** ALTC-Framework-Fasttrack.md  
**Consider:** Claude-Instructions.md (if interaction protocol changes)

### When Examples Need Updates
**Update:** ALTC_Fast_Track_Worked_Example.md

### When NotebookLM Questions Change
**Update:** Human-Usage-NoteBookLM-input-outputs.md

---

## Quick Start for Claude AI

**When generating Fast Track recommendations:**

1. **Start with:** ALTC-Framework-Fasttrack.md (your operational guide)
2. **Reference for definitions:** ALTC-Framework-Definitions.md (when you need detailed explanations)
3. **Reference for format:** ALTC_Fast_Track_Worked_Example.md (see complete example)
4. **Use for origin context:** Altc-origin-story-master.md (understand the "why")

**Remember:** You're generating 30-minute strategic analysis, not 30-hour analysis. Focus over breadth. Positioning over keywords.

---

## Version History

**v2.0 (December 16, 2024)**
- Restructured to reflect reference-based architecture
- Added document architecture explanation
- Marked superseded documents (fork-1, fork-2)
- Added Quick Start section for AI
- Added Document Update Protocol
- Clarified SSOT locations and purposes
- Updated ALTC-Framework-Fasttrack.md status (v2.1)

**v1.0 (December 15, 2024)**
- Initial library index created
