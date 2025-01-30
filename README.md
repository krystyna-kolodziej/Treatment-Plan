# Treatment Plan Generation System

⚠️ **IMPORTANT PRIVACY NOTICE**
- **REMOVE ALL PERSONAL IDENTIFIERS** before inputting any patient data
- Do NOT include: names, dates of birth, addresses, phone numbers, email addresses, medical record numbers, or any other identifying information
- Use only anonymous data for analysis
- Ensure compliance with all applicable privacy laws and regulations
- You are responsible for maintaining patient confidentiality
- When in doubt, exclude any information that could potentially identify a patient

---

A comprehensive system for generating evidence-based treatment plans using standardized clinical guidelines. This system integrates laboratory results, patient context, and established treatment protocols to create structured, consistent treatment recommendations.

## 🚀 Quick Start

1. Copy both the prompt AND treatment guidelines
2. Format your input using the template below
3. Paste everything into Claude in this order:
   - Prompt
   - Treatment Guidelines
   - Patient Information
4. Receive a structured treatment plan

## 📋 System Components

1. **Prompt (`prompt.md`)**
   - Core logic for analysis
   - Input requirements
   - Output formatting rules
   - Guidelines integration logic

2. **Treatment Guidelines (`treatment-guidelines.md`)**
   - Standardized protocols
   - Intervention thresholds
   - Treatment progressions
   - Monitoring requirements

## 📝 Input Template

```markdown
# Patient Analysis Input

Laboratory Results:
[List each result with reference range]
- TSH: X.X (range)
- FT3: X.X (range)
[Continue for all relevant labs]

Patient Information:
- Age: XX
- Biological Sex: X
- Current Symptoms: [List main symptoms]
- Current Medications: [List all current medications]
- Current Supplements: [List all supplements]
- Medical History: [Relevant history]
- Lifestyle Factors: [Key lifestyle elements]

Additional Context:
- Treatment Goals: [List specific goals]
- Preferences: [Any treatment preferences]
- Constraints: [Any limitations]
```

## 📋 Example Input

```markdown
Laboratory Results:
- TSH: 4.8 (0.4-4.0)
- FT3: 2.4 (2.8-4.4)
- FT4: 0.9 (0.8-1.8)
- TPO Antibodies: 250 (<35)
- HbA1c: 5.8% (<5.7)
- Fasting Insulin: 12 (<5)

Patient Information:
- Age: 42
- Biological Sex: Male
- Current Symptoms: Fatigue, weight gain, brain fog
- Current Medications: None
- Current Supplements: Multivitamin
- Medical History: Family history of thyroid disease
- Lifestyle: Sedentary office work, 6hrs sleep

Additional Context:
- Goals: Improve energy, optimize hormones
- Preferences: Prefers natural options initially
- Constraints: Limited exercise time
```

## 🔍 What You'll Receive

A comprehensive treatment plan including:

1. **Clinical Summary**
   - Key findings
   - Indicated protocols

2. **Treatment Recommendations**
   - Specific interventions
   - Dosing instructions
   - Treatment rationale
   - Guideline references

3. **Lifestyle Recommendations**
   - Diet modifications
   - Exercise guidance
   - Sleep optimization
   - Stress management

4. **Monitoring Plan**
   - Follow-up timeline
   - Lab retesting schedule
   - Progress indicators

## 📈 Expanding the System

To add new guidelines:
1. Update `treatment-guidelines.md`
2. Follow the established format
3. Include:
   - Intervention thresholds
   - Treatment protocols
   - Progression criteria
   - Monitoring requirements

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Submit a pull request with:
   - Clear description of changes
   - Rationale for additions
   - Reference to clinical evidence

## 📚 Best Practices

1. **Data Entry**
   - Always anonymize patient data
   - Include all relevant labs
   - Provide complete context

2. **Using the System**
   - Follow the input template exactly
   - Include all required sections
   - Review generated plans carefully

3. **Updating Guidelines**
   - Maintain consistent formatting
   - Include reference ranges
   - Document progression criteria

## 📫 Support

If you need help:
- Open an issue in this repository
- Submit a pull request with improvements
- Contact the maintainers

# Treatment Plan Generation System

📚 [View Instructions for Adding Guidelines](GUIDELINE-INSTRUCTIONS.md) 

[Rest of your README content...]

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Made with ❤️ for healthcare providers committed to evidence-based practice.
