# Changelog

All notable changes to the **Gemini CLI Skills Toolkit** will be documented in this file.

---

## [2026.03.24] - Global Cleanup & Core Sync

### Added
- **AI Operations & Logic**: Introduced a new category for advanced reasoning and routing.
    - `zeroapi`: Intelligent model router for multi-LLM workflows.
    - `agent-browser`: Web browsing and scraping automation.
    - `skill-vetter`: Automated skill validation suite.
    - `control-center`: Central state management for complex tasks.
- **Technical & Data**:
    - `technical-writing`: Professional developer documentation toolkit.
    - `data-visualization`: Automated insight-driven charting.
    - `financial-report-generation`: Structured financial statement tools.
- **Workflow Optimization**:
    - `content-research-writer`: Deep research and citation-backed writing assistant.
    - `context-compression`: Token efficiency and context window management.

### Changed
- **README Overhaul**: Completely reorganized the category structure to better reflect the growing list of capabilities.
- **Global Synchronization**: Pushed 16 previously untracked core skills to the GitHub remote repository.

### Removed
- **OpenClaw & ZeroClaw Integration**: Removed all local dependencies and legacy configurations related to OpenClaw and ZeroClaw to maintain a clean, pure Gemini CLI environment.
- **Gemini API Key Exposure**: Purged all hardcoded Gemini API keys from environment scripts and Skill definitions for enhanced security.

### Fixed
- **Permission Cleanup**: Corrected ownership issues for several skill directories that were previously owned by `root`.

---
## [Legacy] - Initial Release
- Initial set of 40+ skills covering SEO, CRO, and basic Productivity.
