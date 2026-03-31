# CLAUDE-CODE-MAIN-WORKFLOW
All Claude Code Main Workflows and detailed Prompts and Criteria 

# ✨ OpenCode AI Skills Collection

Welcome to the OpenCode AI Skills Collection. Think of this repository as the ultimate playbook for your AI. It provides professional, ready-to-use frameworks that teach your agents how to smartly build software and ruthlessly test it. 

---

## 🏗️ Skill 1: Agentic Architecture

This is your blueprint for running a highly efficient AI software agency. It teaches your system how to organize memory, enforce security, and delegate tasks to specialized bots.

* **The Scenario:** Imagine you are building a complex mobile app. Instead of relying on one overwhelmed AI to write the whole thing, this skill sets up a "manager" AI. The manager delegates frontend work to one bot, backend work to another, and ensures strict rules are followed so no one accidentally deletes your database. 
* **When to Use It:** Use this when you need to design multi-agent swarms, set up strict security boundaries, or organize how your AI remembers project rules.

---

## 🕵️‍♂️ Skill 2: Adversarial Verification

This is your automated, zero-trust Quality Assurance department. It trains your AI to stop blindly trusting code and start actively trying to break it.

* **The Scenario:** Your AI just finished writing a new checkout page for your store. A standard AI might just read the code and say, "Looks good!" This skill forces the AI to actually spin up the server, try to buy an item with a negative price, and physically verify that the system holds up under pressure before giving it a passing grade.
* **When to Use It:** Use this for post-implementation testing, finding bugs, and aggressively verifying that AI-generated code actually works in the real world.

---

## 🚀 How to Get Started

Follow these quick steps to get your AI team up and running:

1. **Install the Files:** Drop the individual `SKILL.md` files directly into your agent's local `.agent/skills/` folder.
2. **Assign the Roles:** * Give the *Agentic Architecture* skill to your main coordinator agent.
   * Give the *Adversarial Verification* skill to a separate, read-only QA agent.
3. **Deploy:** After your main agent finishes a coding task, simply tell your QA agent: *"Verify these changes using the Adversarial Verification methodology."*
