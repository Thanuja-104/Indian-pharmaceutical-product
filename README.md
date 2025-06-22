# Indian-pharmaceutical-product
This dataset contains a comprehensive collection of over 250,000 pharmaceutical products available in India, including details like medicine name, price (INR), manufacturer, packaging, and active compositions.

Each entry reflects structured real-world pharmaceutical product data, useful for analyzing trends in medicine pricing, formulations, discontinued products, and market competition. The dataset was cleaned to remove duplicates, extract quantities from packaging labels, and enrich fields like medicine form and composition structure.

Columns Included:

id: Unique ID for each medicine
name: Brand name of the drug
price_inr: Retail price in Indian Rupees
is_discontinued: Whether the product is active or discontinued
manufacturer_name: Drug manufacturing company
packaging: Original packaging info (e.g., "strip of 10 tablets")
pack_quantity: Number or volume extracted from packaging
pack_unit: Unit of measurement (e.g., tablets, ml)
active_ingredient_1 & active_ingredient_2: Composition of the medicine
* medicine_form: Extracted form such as Tablet, Syrup, Injection, etc.
Possible Use Cases:

Analyzing drug price variations across manufacturers
Identifying top manufacturers or most common drug compositions
Drug recommendation or search engine (based on active ingredients)
* Research in pharmacoeconomics, generic vs. branded pricing
