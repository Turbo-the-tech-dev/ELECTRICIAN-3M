# ELECTRICIAN-3M
information on electrical tape
Master Prompt to Locate All 3M Data on Electrical Tape

Use this prompt to instruct a web research agent, local LLM with web access, or a human researcher to find, collect, and synthesize all authoritative 3M information about electrical tape products. Replace <DATERANGE> and <OUTPUTFORMAT> as needed.

---

Purpose and deliverables
Goal: Locate, retrieve, and synthesize comprehensive 3M product and technical data for electrical tape products (including vinyl electrical tape, rubber splicing tape, high‑temperature tape, self‑fusing tape, and specialty insulating tapes). Deliver a structured, source‑referenced dossier containing datasheets, SDS, technical bulletins, installation guides, approvals/certifications, part numbers, cross‑references, and images/diagrams.  
Primary deliverables:  
- Master inventory of 3M electrical tape SKUs and common cross‑references.  
- Technical summary for each SKU (electrical, mechanical, thermal, adhesive specs).  
- Regulatory and approvals list (UL, CSA, RoHS, REACH, NFPA, etc.).  
- SDS and handling guidance with hazard statements and PPE.  
- Application and installation guidance (recommended uses, surface prep, layering/taping technique).  
- Gaps and follow‑ups: list of missing or ambiguous items and recommended next steps.

---

Scope and inclusion rules
Include: official 3M sources (product pages, technical data sheets, safety data sheets, product catalogs, installation guides, white papers, patents filed by 3M, and 3M press releases). Also include authoritative third‑party sources that reference 3M specs (UL listings, independent test reports, distributor datasheets) only to corroborate or clarify.  
Exclude: user forum posts, unverified retail listings without technical documentation, and copyrighted full‑text reproductions of proprietary manuals beyond short quoted excerpts (quote ≤ 2 lines).  
Time window: search all available historical and current documents; prioritize documents updated within <DATE_RANGE> (e.g., last 10 years) but capture legacy specs if still referenced.

---

Search strategy and example queries
Search approach: combine site‑restricted queries, targeted filetype filters, and product family keywords. Use boolean operators and variations of product names, part numbers, and common 3M series names.

High‑value query templates (copy/paste and adapt):
- site:3m.com "electrical tape" filetype:pdf
- site:3m.com "vinyl electrical tape" "technical data sheet"
- site:3m.com "3M 35" "technical data sheet" OR "datasheet"
- site:3m.com "self-fusing silicone tape" "safety data sheet" filetype:pdf
- site:3m.com "rubber splicing tape" "installation guide"
- "3M" "electrical tape" "UL" OR "CSA" OR "UL 510"
- site:3m.com intitle:"datasheet" "electrical tape" OR "insulating tape"
- site:3m.com "product bulletin" "electrical tape"
- site:3m.com "3M Scotch" "electrical tape" filetype:pdf
- site:3m.com "3M" "electrical insulating tape" "temperature rating"

Advanced search tips:  
- Use filetype:pdf to find datasheets and SDS.  
- Use site:3m.com to restrict to official 3M content; then run parallel searches on site:ul.com, site:standards.org, and major distributors (e.g., site:grainger.com) for corroboration.  
- Search for specific 3M part numbers if known (e.g., 3M 33+, 3M 35, 3M Temflex, 3M Scotch 88) and include hyphen/space variants.

---

Data extraction requirements
For every unique 3M product or document found, extract and record the following fields in a structured table:

- Product name (exact 3M product title)  
- 3M part number / SKU  
- Document type (TDS, SDS, installation guide, UL listing, patent) and URL  
- Document date and last updated (if available)  
- Electrical specs: dielectric strength (V/mil or kV), insulation resistance, breakdown voltage, voltage rating  
- Thermal specs: continuous temperature rating, short‑term max temp, melting/softening points  
- Mechanical specs: tensile strength, elongation at break, thickness (mils/mm), backing material  
- Adhesive properties: adhesive type, tack, peel strength, aging characteristics  
- Environmental/chemical resistance: UV, moisture, solvents, oils, ozone resistance  
- Certifications and approvals: UL file numbers, CSA, RoHS, REACH, NFPA references (cite article/section where applicable)  
- Recommended uses and limitations: splicing, insulating, bundling, high‑temp, outdoor, underground, etc.  
- Installation notes: recommended layering, overlap percentage, surface prep, curing/aging notes  
- SDS hazards and PPE: hazard class, first aid, required PPE, disposal notes  
- Cross‑references: equivalent 3rd‑party part numbers or common substitutes  
- Figure/diagram references: any images or diagrams in the doc (save caption and filename)  
- Direct quotes: up to two short verbatim lines maximum with citation.  
- Confidence score: high/medium/low based on source authority and date.

---

Output format and quality checks
Primary output: <OUTPUT_FORMAT> (choose one: Markdown report, CSV inventory, JSON manifest, or combined). Provide both a human‑readable summary and machine‑readable manifest.

Required sections in the report:  
1. Executive summary (1 page) with key findings and recommended tapes for common journeyman tasks.  
2. Master SKU table (spreadsheet/CSV) with all extracted fields.  
3. Per‑product technical summary (one page each) with specs, approvals, and installation notes.  
4. SDS summary with hazard highlights and PPE.  
5. Certifications appendix listing UL/CSA file numbers and links.  
6. Source index with direct URLs and retrieval dates.  
7. Gaps and next steps listing missing or ambiguous items.

Quality checks to run before finalizing:  
- Verify each URL resolves and the document is downloadable.  
- Confirm datasheet dates and prefer the most recent revision.  
- Cross‑check UL/CSA approvals against the certifier’s database.  
- Ensure no copyrighted full‑text is reproduced beyond allowed short quotes.  
- Flag any conflicting specs and annotate source differences.

---

Reporting and follow‑ups
Cite every factual claim with the source URL and document date. For each product, include the original PDF link and a one‑sentence summary of the document’s purpose. If critical specs are missing (e.g., dielectric strength not listed), mark as MISSING and recommend contacting 3M technical support with the product SKU.






---

I can run this search and produce the master inventory and technical dossier in Markdown and CSV; say Run 3M tape search and I will begin collecting and synthesizing the documents.







#
