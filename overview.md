**Looks like the data has been obtained from here: [Dental Utilization by Provider from State of California](https://catalog.data.gov/dataset/dental-utilization-by-provider-33d9f)**

*Description from source:*
This dataset provides beneficiary and service counts for annual dental visits, dental preventive services, dental treatment, and dental exams by rendering providers (by NPI) for calendar year (CY) 2020. It includes Fee-For-Service (FFS), Geographic Managed Care (GMC), and Pre-Paid Health (PHP) Plans delivery systems. Rendering providers are categorized as either rendering or rendering at a safety net clinic. Beneficiaries are grouped by Age 0-20 and Age 21+.


***Feature Descriptions***

1. **RENDERING_NPI**: The National Provider Identifier (NPI) of the healthcare professional who provided the medical service or procedure.

2. **PROVIDER_LEGAL_NAME**: The legal name of the healthcare provider or facility.

3. **CALENDAR_YEAR**: The year the services were provided.

4. **DELIVERY_SYSTEM**: The type of health plan or payment model, which can be Fee-For-Service (FFS), Geographic Managed Care (GMC), or Pre-Paid Health (PHP).

5. **PROVIDER_TYPE**: The type of healthcare professional.
    - **RENDERING** \
    This refers to a standard healthcare provider who renders (or provides) services. This could be a dentist in a private practice, a small group practice, or a larger clinic that is not specifically designated to serve a high-need population. They are the professional who directly provided the service.
    
    - **REDERING SNC** \
    This is a rendering provider who works at a Safety Net Clinic. These clinics are defined as healthcare providers that offer care to a large number of uninsured, underinsured, or otherwise vulnerable patients. They are typically non-profit organizations that serve low-income, inner-city, or rural communities.

6. **AGE_GROUP**: The age range of the patients receiving the services. ["0-20", "21+"]

7. **ADV_USER_CNT**: The number of unique beneficiaries who received Advanced services.

8. **ADV_USER_ANNOTATION_CODE**: A code providing additional information about the ADV (advanced) users.

9. **ADV_SVC_CNT**: The total count of Advanced services provided.

10. **ADV_SVC_ANNOTATION_CODE**: A code providing additional information about the ADV (advanced) services.

11. **PREV_USER_CNT**: The number of unique beneficiaries who received Preventive services.

12. **PREV_USER_ANNOTATION_CODE**: A code providing additional information about the PREV (preventive) users.

13. **PREV_SVC_CNT**: The total count of Preventive services provided.

14. **PREV_SVC_ANNOTATION_CODE**: A code providing additional information about the PREV (preventive) services.

15. **TXMT_USER_CNT**: The number of unique beneficiaries who received Treatment services.

16. **TXMT_USER_ANNOTATION_CODE**: A code providing additional information about the TXMT (treatment) users.

17. **TXMT_SVC_CNT**: The total count of Treatment services provided.

18. **TXMT_SVC_ANNOTATION_CODE**: A code providing additional information about the TXMT (treatment) services.

19. **EXAM_USER_CNT**: The number of unique beneficiaries who received Exam services.

20. **EXAM_USER_ANNOTATION_CODE**: A code providing additional information about the EXAM (exam) users.

21. **EXAM_SVC_CNT**: The total count of Exam services provided.

22. **EXAM_SVC_ANNOTATION_CODE**: A code providing additional information about the EXAM (exam) services.

The repeating pattern of USER_CNT, SVC_CNT, and ANNOTATION_CODE suggests the data is a summary of different types of healthcare services—specifically, Advanced, Preventive, Treatment, and Exam services—grouped by provider and calendar year.

