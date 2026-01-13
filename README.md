# SENECA

A GitHub Action for daily stoic reflection.

> "You could leave life right now. Let that determine what you do and say." — Marcus Aurelius

This repository contains a GitHub Action that posts daily reminders about mortality and virtue. Every day, a new stoic quote appears in your Issues. Once a year, on January 1st, you receive a longer reflection on the past year and the time you have left.

The purpose is simple: to remember that you will die, and to let that truth clarify how you live.

## What This Does

- Posts a daily GitHub Issue with a stoic quote or philosophical reflection
- Closes the previous day's reminder automatically
- Posts an annual reflection on January 1st
- Runs without any manual intervention

The quotes come from Marcus Aurelius, Seneca, Epictetus, and other philosophers who understood that awareness of death isn't morbid—it's clarifying.

---

## Sample Quotes

From the collection of over 240 reflections:

"Memento mori: Remember, you must die. This is not a curse, but the most profound truth that liberates you from triviality."

"It is not that we have a short time to live, but that we waste a lot of it." — Seneca

"You have power over your mind—not outside events. Realize this, and you will find strength." — Marcus Aurelius

"What upsets people is not things themselves, but their judgments about these things." — Epictetus

"The impediment to action advances action. What stands in the way becomes the way." — Marcus Aurelius

"When we are no longer able to change a situation, we are challenged to change ourselves." — Viktor Frankl

---

## Installation

Create a file at `.github/workflows/memento-mori.yml` in your repository.

Copy the contents from [this workflow](./.github/workflows/memento-mori.yml).

Commit and push. The action will run automatically.

---

## Schedule

- Daily at 10 AM UTC — New stoic reminder
- January 1st at 12 PM UTC — Annual reflection

You can also trigger it manually from the Actions tab.

---

## Why

Because procrastination is a luxury for the immortal. You're not immortal.

The Stoics believed that remembering death—memento mori—isn't about fear or pessimism. It's about focus. When you internalize that your time is finite and uncertain, the trivial falls away. What remains is what actually matters: character, contribution, relationships, growth.

This action won't make you productive. It won't solve your problems. It will just remind you, every day, that the clock is running.

What you do with that reminder is up to you.

---

## Customization

The workflow file contains over 240 quotes organized by theme:
- Core Memento Mori foundations
- Marcus Aurelius on mortality and virtue
- Seneca on time and wisdom
- Epictetus on control and freedom
- Reflections on discipline, suffering, courage, acceptance

You can add your own quotes, adjust the schedule, or modify the issue format.

---

## Final Thought

You could leave life right now.

Or you could start that thing you've been putting off. Stop wasting time on things outside your control. Live like it matters.

The choice is yours. The time is now.
