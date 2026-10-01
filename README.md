# JD Resume Tailoring

A Codex skill for tailoring an existing resume to a specific job description. It maps role requirements to evidence in the resume and optional career materials, proposes changes, and waits for confirmation before producing the final version.

## What it does

- Identifies hard requirements, core responsibilities, and preferred qualifications in a job description.
- Links each requirement to evidence in the supplied resume or supporting materials.
- Distinguishes wording gaps, missing information, insufficient evidence, and confirmed skill gaps.
- Preserves the source resume's language, section order, and approximate length.
- Produces a complete tailored resume and an evidence-backed change log after the plan is approved.

The skill does not invent qualifications, metrics, responsibilities, or ownership. It does not provide ATS scores or guarantee application outcomes.

## Use

Provide:

1. The job description text, or an accessible job posting URL.
2. The resume to use as the starting point.
3. Optional experience notes, project retrospectives, or other materials that can support facts missing from the resume.

The first response contains an evidence map and an edit plan. Review it and reply **“确认”** to receive the tailored resume. Supporting materials are only added after their use is shown in the plan and approved.

## Install

Copy this repository folder into either:

- Personal skills: `~/.codex/skills/jd-resume-tailoring/`
- Project skills: `.agents/skills/jd-resume-tailoring/` under the project root.

Then invoke the skill with `$jd-resume-tailoring` or ask for a resume to be tailored to a job description.

## Files

- `SKILL.md` — full skill instructions and workflow.

No license is included. Add a license if you intend to grant public reuse rights.
