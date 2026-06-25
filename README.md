# FDA FAERS Adverse Event Text Analysis
A reusable Python tool for extracting and analyzing case reports from the FDA's FAERS (Adverse Event Reporting System) database, built for an investigative reporting project on kratom and federal drug regulation. In this case, I analyzed .txt/.pdf files of FDA Adverse Event Reports for kratom, 7-hydroxymitragynine, and mitragynine psuedoindoxy (from the first reported case of kratom/kratom derivative exposure through December 1, 2025).

## What it does:

Downloads and cleans FAERS case report data, converts to text format for NLP analysis, and extracts structured findings including serious vs. non-serious case counts, year-over-year reporting trends, most common concomitant drugs, patient demographics, reasons for use, adverse reactions, and frequently cited medical literature.
### Built with: pandas, spaCy (en_core_web_trf), regex, rapidfuzz, tabular-2-text, fuzzy-context-finder
### Adaptable for: Any substance or drug category available in the FAERS database. Swap in a new product name and rerun.
### Background: Built as part of an investigation into how the FDA's MGPS algorithm handles reporting on legal, unregulated substances like kratom and its synthetic derivatives. See also: FDA FAERS dashboard

## Notes on use Downloaded excel files from FDA FAERS system and analyze:
<ol>
1. The number of serious vs non-serious cases
2. The counts for each year (beginning in 2015)
3. The most common product names
4. The most common reason for use
5. The most common reactions
6. The average patient age
7. What reference literature is most commonly used for each case (where applicable)
</ol>

