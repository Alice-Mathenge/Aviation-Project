# Aviation Accidents and Incidents Data Analysis

## Overview
This project analyzes historical aviation accidents and incidents data (1962–2023) to provide **actionable insights** for safer aircraft purchase decisions. The analysis focuses on identifying lower-risk aircraft categories, safer makes and models, and key contextual factors affecting accident severity.

---

## Business Understanding
The company is launching a new aviation venture. The key business questions include:

- Which aircraft categories have lower accident severity?
- Which aircraft makes and models are associated with safer operations?
- How do weather, flight purpose, and phases of flight impact accident severity?

The goal is to support **data-driven aircraft purchase decisions** for safer and more cost-effective operations.

---

## Data Understanding and Analysis

**Source of Data:** [Kaggle - Aviation Accidents and Incidents Dataset](https://www.kaggle.com/)  

**Dataset Description:**  
- 88,889 records spanning from 1962 to 2023  
- 22 columns including aircraft category, make, model, injury severity, flight purpose, phase of flight, weather, and number of injuries.  

**Sample Columns:**
- `Aircraft.Category`
- `Make`
- `Model`
- `Purpose.of.flight`
- `Broad.phase.of.flight`
- `Weather.Condition`
- `Total.Fatal.Injuries`
- `Total.Serious.Injuries`
- `Total.Minor.Injuries`
- `Total.Uninjured`
- `Injury_Severity`

---

## Dashboard

Below are the key visualizations summarizing injury severity across aircraft categories, manufacturers, and flight contexts:

| Aircraft Category Risk | Manufacturer/Model Safety | Contextual Risk Factors |
|------------------------|--------------------------|------------------------|
| ![Aircraft Category](visualizations/proportion_injury_severity_by_aircraft.png) | ![Aircraft Make](visualizations/proportion_injury_severity_by_make.png) | ![Flight Phase](visualizations/injury_by_phase.png) |
| Lower injury severity in Powered-Lift & Ultralight categories. | Boeing shows higher non-fatal/unknown injuries; other manufacturers mostly fatal. | Most severe accidents occur during Landing, Takeoff, and Maneuvering. |

---

## Recommendations
Based on the analysis, the following recommendations are proposed:

1. **Prioritize safety interventions** for high-risk categories such as Airplanes and Helicopters.
2. **Focus on general aviation manufacturers** like Cessna and Piper to enhance pilot training and maintenance standards.
3. **Reduce risk in personal-use flights**, especially during Landing and Takeoff phases.

---

## Conclusion
The analysis highlights the following key findings:

1. **High overall risk:** Most aircraft categories have a high proportion of fatal injuries.  
2. **Safer categories exist:** Powered-Lift and Ultralight aircraft show less severe injuries.  
3. **Manufacturer insights:** Boeing aircraft involved in accidents tend to have lower fatality rates, possibly due to design or operational factors.  


### Three Relevant Findings
- Categories like Powered-Lift and Ultralight have a lower proportion of fatal injuries.  
- Boeing aircraft have more non-fatal/unknown injury accidents than other manufacturers.  
- Landing and takeoff phases account for most severe accidents, emphasizing human/operational risk.

**Key risk drivers:** Human and operational factors during personal flights, often in good weather.  
**Recommendation:** Aircraft selection should prioritize business or instructional use for safer and cost-effective operations.

---

## Contact
**Alice Wangui Mathenge**  
Phone: 0727673400  
Email: mathengealice709@gmail.com
