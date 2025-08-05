# strokethrombolysis
Decision algorithm app for stroke thrombolysis

# Acute Ischaemic Stroke Decision Algorithm

[![License: AGPL-V3](https://img.shields.io/badge/License-AGPLv3-yellow.svg)]([https://opensource.org/licenses/AGPLv3](https://opensource.org/license/agpl-v3))
[![GitHub Pages](https://img.shields.io/badge/demo-live-green.svg)](https://dcicantab5.github.io/strokethrombolysis/)

An evidence-based clinical decision support tool for acute ischaemic stroke management, incorporating the latest guidelines for IV thrombolysis and mechanical thrombectomy decisions.

## TIME IS BRAIN

**Every minute counts!** Rapid assessment and treatment are essential for optimal outcomes in acute ischemic stroke.

## Live Demo

Access the tool here: [https://dcicantab5.github.io/strokethrombolysis/](https://dcicantab5.github.io/strokethrombolysis/)

## Overview

This interactive web application guides healthcare providers through the critical decision-making process for acute ischaemic stroke treatment, based on:
- 2019 AHA/ASA Guidelines for Early Management of Acute Ischaemic Stroke
- Recent trials including DAWN, DEFUSE 3, ANGEL-ASPECT, and SELECT2
- Current best practices for extended window therapies

## Clinical Workflow

### Initial Assessment Requirements

1. **Clinical Evaluation**
   - Establish high probability of acute ischemic stroke
   - Sudden focal neurological deficits

2. **Confirm LKW (Last Known Well)**
   - Determine exact time patient was last in baseline state
   - Critical for treatment window determination

3. **Assess Severity**
   - NIHSS (National Institutes of Health Stroke Scale)
   - Score 0-42 (higher = more severe)
   - ≥6 indicates disabling stroke

4. **Neuroimaging**
   - NCCT to exclude intracerebral hemorrhage
   - CTA/MRA to identify vessel occlusion
   - Calculate ASPECTS score

5. **Laboratory**
   - Blood glucose (exclude hypoglycemia)
   - Coagulation studies if indicated

## Primary Treatment Options

### IV Thrombolysis (0-4.5 hours)
- **Medications**: Alteplase or Tenecteplase
- **Dosing**: 
  - Alteplase: 0.9 mg/kg (max 90 mg), 10% bolus, 90% over 60 min
  - Tenecteplase: 0.25 mg/kg bolus (max 25 mg)
- **Benefits**: Time-dependent (best within 90 minutes)
- **Risk**: Symptomatic ICH ~3.4%
- **BP Management**: <185/110 during, <180/105 for 24h after

### Mechanical Thrombectomy (0-24 hours*)
- **Indications**: Large vessel occlusion (LVO)
- **Time Windows**:
  - 0-6 hours: ASPECTS ≥6, standard eligibility
  - 6-24 hours: Requires perfusion imaging (DAWN/DEFUSE 3 criteria)
  - Large core (ASPECTS 3-5): Up to 24 hours with recent evidence
- **Locations**: ICA, M1, M2, or basilar artery
- **Notes**: Can combine with IV thrombolysis ("bridging therapy")

*Basilar occlusion: up to 24 hours with PC-ASPECTS ≥6

## Major Contraindications to IV Thrombolysis

- Active bleeding or recent major surgery
- Recent use of DOACs (within 48h)
- Severe uncontrolled hypertension (>185/110 mmHg)
- Platelet count <100,000/mm³
- INR >1.7 or PT >15 seconds
- Blood glucose <50 mg/dL
- Previous stroke within 3 months
- Head trauma within 3 months
- GI/GU hemorrhage within 21 days
- Major surgery within 14 days

## Alternative Treatments

### Not Eligible for Thrombolysis/Thrombectomy?

**Minor Strokes (NIHSS ≤5)**
- Dual antiplatelet therapy within 24-72 hours
- Clopidogrel 300-600mg + Aspirin 81-325mg
- Continue for 21-90 days, then single antiplatelet

**All Other Patients**
- Aspirin 160-300mg within 48 hours
- Continue for secondary prevention

## Decision Algorithm Features

The web application includes:
- **Step-by-step assessment** workflow
- **Automatic time window calculations**
- **Real-time eligibility determination**
- **Evidence-based recommendations**
- **Post-treatment management guidance**

## Post-Treatment Management

- Monitor neurological status closely
- Maintain appropriate BP targets
- Hold antithrombotics for 24h after thrombolysis
- Admit to stroke unit or neuro ICU
- Initiate secondary prevention measures

## 🚀 Quick Start Guide

### For Users:
1. Navigate to the [live application](https://dcicantab5.github.io/strokethrombolysis/)
2. Follow the step-by-step assessment
3. Input patient data as prompted
4. Review generated recommendations
5. Always apply clinical judgment


## Technology Stack

- **React 18** - UI framework
- **Tailwind CSS** - Styling
- **Babel** - JSX transformation
- **GitHub Pages** - Hosting

## Compatibility

- Modern web browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- No installation required
- Works offline after initial load

## Disclaimer

This tool is designed for educational purposes and clinical decision support. It should not replace clinical judgment or institutional protocols. Always consult current guidelines and consider individual patient factors when making treatment decisions.

## Evidence Base

Based on major clinical trials and guidelines:
- MR CLEAN, ESCAPE, SWIFT PRIME, REVASCAT (2015)
- DAWN (2018) - Extended window thrombectomy
- DEFUSE 3 (2018) - Perfusion-based selection
- WAKE-UP (2018) - MRI-guided thrombolysis
- EXTEND (2019) - Perfusion-guided thrombolysis
- ANGEL-ASPECT (2023) - Large core thrombectomy
- SELECT2 (2023) - Large core thrombectomy
- AHA/ASA Guidelines (2019 Update)

## Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the AGPL-v3 License - see the [License: AGPL-V3](https://opensource.org/license/agpl-v3) file for details.

## Authors

- Clinical Content: Based on AHA/ASA Guidelines
- Web Application: Dr Saiful Safuan Bin Md Sani

## Acknowledgments

- American Heart Association/American Stroke Association

## Support

For issues or questions:
- Open an issue on GitHub
- Contact: [dcicantab5@icloud,com]

---

**Remember: In acute stroke care, TIME IS BRAIN. Every minute counts!**

*Last updated: 5 AUGUST 2025*
