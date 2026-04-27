Executive Summary
Analysis of 500,000 products from Open Food Facts revealed 
that the snack market is dominated by high-sugar, low-protein 
products. The biggest Blue Ocean opportunity is in [YOUR CATEGORY], 
where products with [X]g protein and less than [Y]g sugar per 100g 
are severely under-represented. Top protein sources identified: 
Whey, Soy, and Peanuts. Blue Ocean products that also score A/B 
on Nutri-Score represent the highest-value launch targets.

## Project Links
- Notebook: [https://colab.research.google.com/drive/1S-Cn8NWxBoz5goubjpkMIOhzWSyFNcUi?usp=sharing]
- Dashboard: [https://datastudio.google.com/reporting/ba383244-ee18-44d1-87cd-c2f55671273b]  
- Presentation: [https://docs.google.com/presentation/d/1MCckCvZi1Yz9M5goopP6epAv4eDEos-k/edit?usp=drivesdk&ouid=103288338254878318951&rtpof=true&sd=true]

## Technical Notes
- Cleaned 500K rows: dropped nulls in critical fields, 
  filtered impossible nutrient values (0-100g range)
- Categories: parsed categories_tags column, assigned 8 
  high-level buckets via keyword matching
- Candidate's Choice: Added Nutri-Score filter to identify 
  products that are BOTH Blue Ocean AND grade A/B — giving 
  R&D a commercially launch-ready shortlist
