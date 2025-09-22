# Data_Analyst-Task-1
Cleaning and preparing a raw dataset by handling null values, removing duplicates, and fixing inconsistent formats.

Raw Netflix dataset had missing values, inconsistent formats, and unstandardized column names.

Missing values: director → "Unknown", cast → "Not Available", country & rating → most frequent values.

date_added converted to proper datetime (10 invalid entries remain missing).

No duplicate rows found; type column standardized ("Movie", "TV Show").

Column headers renamed to lowercase with underscores for consistency.

title column removed; data filtered and sorted by release_year to focus on latest releases.

Final dataset is free of duplicates and inconsistencies, with only minor unavoidable date gaps, ready for clustering and analysis.
