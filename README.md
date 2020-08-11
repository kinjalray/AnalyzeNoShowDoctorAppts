# AnalyzeNoShowDoctorAppts

## Purpose:
Exploring doctor appointment data to understand which factors determine likelihood of the patient showing up to appointment

**Data Source:** https://www.kaggle.com/joniarroba/noshowappointments

## Relationships Explored
- No-Show vs. Gender
- No-Show vs. (Schedule Date to Appointment Date time frame)
- No-Show vs. (Affiliation with Welfare Program)

## Conclusions/Follow-Ups

My exploration in this dataset has led me to the following conclusions (conclusions for this dataset only, not for the entire population):

- Younger Ages, around the age of 33, are more likely to be a no-show
- Gender does not play a role in whether a patient shows up
- Those who make appointments ahead of time are more likely to show up
- If the patient is on welfare, there is a slightly higher likelihood that they will not show up.

### Considerations

I explored a few of many possible relationships in the dataset. For further analysis, it could be informative to look at the relationship between Neighborhood and No-show, SMS-Received and No-show, etc.

Neighborhood and No-show: The location of a single hospital in a particularly inconvenient, or run-down area could skew results.

SMS-Received and No-show: Effect of receiving an SMS reminder regarding the appointment could be stronger than the relationships I explored above.

###Further Steps

Next steps would include bootstrap sampling and hypothesis testing to obtain sufficient evidence in concluding whether the observations are statistically significant regarding the population.
