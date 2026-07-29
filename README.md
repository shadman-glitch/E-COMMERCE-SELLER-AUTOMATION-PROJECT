 <img width="1239" height="446" alt="image" src="https://github.com/user-attachments/assets/a2f78a76-f545-4e98-9670-2ba983ad9dae" />

<img width="1232" height="421" alt="image" src="https://github.com/user-attachments/assets/ab43c8fc-55ef-4b47-ae9b-cef8a439e219" />

<img width="1099" height="221" alt="image" src="https://github.com/user-attachments/assets/9a7e6fca-1461-4817-ba7f-8c6ecc4c4f1d" />


# E-COMMERCE-SELLER-AUTOMATION-PROJECT
PROJECT FOR AUTO DATA ENTRY , ORDER HANDELING AND REPLY WITH ADVANCED DATASETS OF INFORMATION OF THE DEDICATED STORE.
JUST SHIPPED THE MOST COMPLEX SYSTEM I'VE EVER BUILT IN MY ENTIRE AUTOMATION CAREER. 35 DAYS OF WORK. And it's live, in production,ready to sell.
I built a fully autonomous AI sales and CRM system for Instagram e-commerce sellers. The kind of system that replaces 2-3 employees and runs 24/7 without breaks, sick leaves, or attitude problems. And I'm selling it at ₹3,500/month.
Here's what this system actually does in production.
A customer DMs an Instagram store. Within 5 seconds, the AI reads the message, figures out the intent, and replies in natural Hinglish/English not like a chatbot, like a real person. It handles product inquiries, casual conversations, bargaining,everything. Pure LLM intelligence with strict behavioral guardrails I engineered over weeks of testing with real customers. 
The entire architecture runs on n8n with modular sub-workflows. One sub-workflow handles the AI chat agent Mistral LLM connected to a Pinecone vector database running Google Gemini embeddings at 3072 dimensions for product search. When a customer says "black dress dikhao", it doesn't guess. It runs a real vector similarity search, pulls the exact matching product from the catalog, and sends the actual product image directly into the DM through the Instagram Graph API. The second sub-workflow is a full CRM and order automation pipeline. The moment a customer confirms an order inside the DM, the system extracts their name, shipping address, phone number, product ID, price parses everything automatically from the conversation text and pushes it straight into Airtable. A real-time Slack alert fires to the fulfillment team. Zero manual data entry. Zero missed orders.
Then there's the Vision AI layer. Customer sends a screenshot of a product they saw somewhere? The system analyzes the image, matches it against the product database, and replies with the exact item name, price, availability. Someone shares a Reel or Post into the DM? The system extracts the Instagram Media ID, looks up which product was featured in that content, and responds with full details. All automatic.
Comment automation is built in too. Someone comments "price?" on any post or reel the AI replies publicly to the comment AND sends a personalized DM to that user with product info. I also built an Advanced RAG knowledge base layer through Pinecone for company-level queries. Store locations, payment methods, shipping policies, privacy policy all embedded as 3072-dimension vectors. So when someone asks "kahan located ho?", the AI retrieves the real physical store addresses from the vector database. No hallucinations.
