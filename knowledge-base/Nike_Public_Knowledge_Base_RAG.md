# NIKE Public Knowledge Base

**Unofficial portfolio demo — RAG-ready corpus**  
**Knowledge-base ID:** `nike-public-kb-v1.0`  
**Reviewed:** 30 July 2026  
**Primary scope:** Global company information; U.S. shopping-policy examples  
**Intended use:** n8n + Supabase retrieval-augmented generation portfolio demo  
**Source standard:** Official NIKE, Inc. and Nike.com pages only

> **Important disclaimer:** This document is an independent educational portfolio resource created from publicly available official Nike sources. It is not produced, approved, endorsed, or operated by NIKE, Inc. It must not be presented as official Nike customer support. Policies and availability can vary by country and can change after the review date.

## 1. How This Knowledge Base Should Be Used

This file is designed as a factual retrieval corpus. Each section is written so that a chunk can stand on its own when returned by vector search. The chatbot should answer only from retrieved content and should not claim access to Nike systems, private order data, inventory, customer accounts, or internal company records.

- Use the term **NIKE, Inc.** for the corporation and **Nike** for the consumer brand when the distinction matters.
- Treat prices, shipping thresholds, return windows, service hours, product availability, and promotions as region-specific and time-sensitive.
- Shopping-policy examples in this document are based on Nike's U.S. help pages as reviewed on 30 July 2026.
- When a user's country is unknown, ask for the country or direct the user to the local Nike Help page before giving a region-specific policy.
- Never describe this chatbot as official Nike support or imply endorsement by NIKE, Inc.
- For unsupported facts, say the information was not found in the knowledge base rather than guessing.

**Recommended fallback response:**  
“I could not find that information in this Nike public knowledge base. Policies and availability may vary by country, so please check the official Nike Help page for your region.”

## 2. Company Overview

NIKE, Inc. is a global sports company based in Beaverton, Oregon. The company describes itself as serving athletes and keeping athletes at the center of its work. NIKE, Inc. includes the Nike, Jordan, and Converse brands and develops products, services, and experiences for sport and everyday athletic lifestyles.

Nike's public mission is to bring inspiration and innovation to every athlete in the world. Nike explains the word athlete broadly with the statement: “If you have a body, you are an athlete.” Its public purpose is to move the world forward through the power of sport.

Nike's work spans performance innovation, product design, digital services, membership experiences, retail, wholesale distribution, community initiatives, and sustainability programs. Its broad commercial product groups include athletic footwear, apparel, equipment, and accessories.

For fiscal year 2026, ended 31 May 2026, NIKE, Inc. reported full-year revenue of USD 46.4 billion. This figure is time-sensitive and should always be stated with the fiscal year and period end date.

**Source tags:** S1, S2, S3, S19

## 3. Mission, Purpose, and Athlete-Centered Approach

Nike publicly frames innovation as more than product engineering. The company connects innovation with enabling athletic performance, removing barriers, expanding access to sport, and protecting the future of sport.

Recurring public-purpose themes include:

- **Innovation:** creating and improving products, services, and experiences for athletes.
- **Access and community:** supporting participation in sport and helping more people experience play and movement.
- **Sustainability:** reducing environmental impact and protecting the environments in which sport takes place.

**Source tags:** S1

## 4. History and Corporate Structure

Nike's origin story begins with coach Bill Bowerman and his former University of Oregon athlete Phil Knight. According to Nike's official archive, the two agreed to a business partnership on 25 January 1964, creating Blue Ribbon Sports. Bowerman's interest in designing lighter and faster footwear and Knight's business ambitions became central to the company's early development.

Today, NIKE, Inc. operates as a multi-brand company comprising Nike, Jordan Brand, and Converse. The company's principal headquarters is the Philip H. Knight Campus in Beaverton, Oregon. Corporate leadership and organizational information can change, so the official NIKE, Inc. company page should be used for current leadership details.

**Source tags:** S3, S4

## 5. Products and Shopping Categories

Nike develops and markets athletic and sport-inspired products. The exact assortment varies by country, season, sport, age group, and sales channel.

Common high-level product groups include:

- Footwear: performance and lifestyle shoes for running, basketball, football/soccer, training, tennis, golf, skateboarding, outdoor use, and everyday wear.
- Apparel: tops, bottoms, jackets, shorts, tights, sports bras, uniforms, socks, and sport-specific clothing.
- Equipment and accessories: bags, balls, gloves, hats, headwear, shin guards, water bottles, and other sport or lifestyle accessories.
- Jordan Brand products: basketball and lifestyle footwear, apparel, and accessories associated with Jordan Brand.
- Nike By You products: selected customizable footwear available through Nike's digital customization experience.

Nike product pages may include intended use, design features, materials, colorways, size options, fit notes, price, availability, and customer reviews. Product availability and specifications should be confirmed on the relevant local product page.

**Source tags:** S2, S7, S19

## 6. Nike Membership and Digital Services

Nike Membership is free to join. Nike describes Membership as a way to access products, guidance, experiences, special offers, information about new releases, and eligible shipping benefits. Specific benefits can differ by country and over time.

Examples include member product access, selected experiences or offers, order-history features, receiptless return support for eligible purchases, Nike By You access, and digital sport and wellness services.

### 6.1 Nike App, SNKRS, Nike Run Club, and Nike Training Club

- **Nike App:** shopping, product discovery, membership features, and access to Nike services.
- **SNKRS:** information and access mechanisms for selected sneaker launches and releases.
- **Nike Run Club (NRC):** run tracking, running goals, guided runs, challenges, and training support.
- **Nike Training Club (NTC):** workouts, training guidance, and wellness-oriented content.

Features and compatibility can vary by app version, device, and region.

**Source tags:** S5, S6

## 7. Product Advice, Size, and Fit

Nike provides product-advice resources through Nike.com and the Nike App. These resources can include buying guides, product-care guidance, styling information, size charts, and assistance from Nike Experts, subject to local availability.

### 7.1 Size and Fit Guidance

Nike recommends using the appropriate Nike size chart and the size guide linked on the exact product page.

- Use the exact product page when possible because fit can vary across models.
- Do not convert sizes from memory when an official chart is available.
- For performance footwear, consider intended sport, width, cushioning preference, and fit notes in addition to numeric size.
- If fit is uncertain, check the local return or exchange policy before purchase.

**Source tags:** S8, S9

## 8. Nike By You Customization

Nike By You is a customization experience for Nike Members. For eligible shoe models, users can choose from curated colors and materials and view the evolving design in a three-dimensional builder. Selected styles may allow a Personal iD or signature-style customization, subject to Nike's personalization guidelines.

Availability, eligible models, production time, pricing, return eligibility, and personalization options vary by market and product.

**Source tags:** S7

## 9. U.S. Shopping and Order Policies

> **Regional limitation:** Sections 9 through 12 summarize Nike's U.S. help pages as reviewed on 30 July 2026. They must not be presented as universal global policy.

### 9.1 Shipping Options — U.S. Example

Nike's U.S. help page displays available shipping speeds and estimated delivery dates during checkout. Shipping prices and eligibility depend on membership status, order value, delivery address, item availability, and available shipping method.

As reviewed on 30 July 2026, Nike's U.S. page stated that Nike Members receive free standard shipping on qualifying orders of USD 50 or more, while guest thresholds and shipping fees differ. It also described expedited options, free same-day pickup for eligible products at participating stores, and shipment to selected pickup locations.

- Multi-item orders may be divided into multiple deliveries.
- A shipping confirmation can be issued for each shipment.
- Estimated delivery dates are shown during checkout and can change.
- Nike By You and Converse Custom orders may follow different delivery timelines.
- International shipping rules depend on the local Nike site and destination.

**Source tags:** S10

### 9.2 Tracking an Order — U.S. Example

Nike Members can sign in and review order history on Nike.com or in the Nike App. After shipment, the order page can display the carrier, tracking number, and estimated delivery date. Guest customers can access order status using the order number and email address used for purchase.

Orders containing multiple items may arrive in separate packages. A “label created” status generally means a shipping label exists but the carrier may not yet have scanned the package. Nike's help page stated that this stage can take up to 72 hours before carrier movement appears.

**Source tags:** S11

### 9.3 Changing or Cancelling an Order — U.S. Example

Nike's U.S. help page states that an order cannot be edited after placement, including color, size, quantity, delivery address, shipping option, or other order details.

As reviewed on 30 July 2026, eligible orders could be cancelled within 30 minutes after placement. Members can open the order in their account, while guests can use the order number and email address. If the cancellation button is unavailable, the order is no longer eligible for cancellation. This window is time-sensitive and region-specific.

**Source tags:** S12

## 10. Returns and Exchanges — U.S. Example

Nike's U.S. return policy, as reviewed on 30 July 2026, stated that most eligible Nike.com, Nike App, and Nike store purchases could be returned or exchanged within 60 days of online delivery or store purchase. Proof of purchase is required and exceptions apply.

- Items bought from another retailer generally must be returned to that retailer.
- Nike Clearance store purchases and returns have special restrictions.
- Selected customized, collaboration, or sealed products may have specific exceptions.
- Nike Members may receive free return shipping for eligible U.S. returns; guest rules can differ.
- Returned items are inspected before a refund or exchange is completed.

The local help page should always be checked for current steps, exclusions, and refund timing.

**Source tags:** S13, S14

## 11. Product Quality and Warranty — U.S. Example

Nike states that it stands behind its shoes and gear. Its U.S. help page explains that an item believed to have a material or workmanship flaw may be eligible for inspection. As reviewed on 30 July 2026, the page referenced a period within two years of the manufacture date for many products, while certain products can have specific written warranties or different periods.

The correct process depends on where the product was purchased and how long ago it was purchased.

**Source tags:** S18

## 12. Product Care

Nike's product-care guidance emphasizes checking the item's care label and using methods appropriate to the material. For shoes, Nike generally recommends hand cleaning rather than using a washing machine.

### 12.1 General Shoe-Cleaning Process

1. Remove loose dirt with a dry, soft-bristled brush or clean toothbrush.
2. Mix a small amount of mild detergent or dish soap with water. Avoid concentrated soap or harsh chemicals.
3. Remove the laces and clean them separately.
4. Gently clean the outsole and midsole with the mild solution.
5. Clean the upper carefully using a soft brush or cloth appropriate to the material.
6. Blot away moisture and dirt instead of aggressively rubbing the material.
7. Allow shoes and removable components to air-dry completely at room temperature.

Leather and suede require more careful spot-cleaning, while knit or mesh shoes should be brushed gently. Nike does not recommend machine-washing shoes because it may damage the footwear and washing machine. Heat from a dryer can also damage shoes, so air-drying is preferred.

For apparel such as Nike Dri-FIT products, follow the garment's care label. A chatbot should not invent a washing temperature, detergent requirement, or drying method when the product label is unavailable.

**Source tags:** S16, S17

## 13. Sustainability and Circularity

Nike describes **Move to Zero** as its journey toward zero carbon and zero waste to help protect the future of sport. Public sustainability content focuses on carbon, waste, water, chemistry, materials, product longevity, and circular solutions.

- Materials with lower environmental impact.
- Waste reduction and circularity.
- Product care to extend useful life.
- Recycling and donation programs in selected locations.
- Nike Grind uses manufacturing scrap and end-of-life footwear materials in products and surfaces.
- Selected refurbished or re-created product programs may give eligible products or materials another use.

Program availability and eligibility differ by market and location. A chatbot should not promise a specific store accepts recycling or a specific product qualifies without checking current local program information.

**Source tags:** S15

## 14. Customer Support and Escalation

Nike's Help site organizes assistance around returns and exchanges, shipping and delivery, orders and payment, shopping, membership and apps, and company information. Contact methods and hours vary by country and can change.

- For order-specific support, direct users to the official order-status page or local Nike Help contact options.
- For purchases from another retailer, direct users to the original retailer unless official Nike warranty guidance says otherwise.
- For local store availability, use the official Nike store locator.
- For suspected defects, use official warranty or claim instructions for the purchase region.
- For account, payment, or personal-data issues, do not request sensitive information in the chatbot; direct the user to official secure support.

### Privacy rule for the demo chatbot

Do not ask users to provide passwords, full payment-card numbers, one-time codes, government ID numbers, or other highly sensitive information. This public RAG chatbot cannot authenticate Nike accounts or access real Nike orders.

**Source tags:** S20

## 15. Retrieval-Friendly FAQ

**Q: Is this an official Nike chatbot?**  
A: No. It is an independent educational portfolio demo using publicly available official Nike information. It is not affiliated with, endorsed by, or operated by NIKE, Inc.

**Q: What is Nike's mission?**  
A: Nike's public mission is to bring inspiration and innovation to every athlete in the world. Nike explains that if a person has a body, that person is an athlete. [S1]

**Q: What is Nike's purpose?**  
A: Nike describes its purpose as moving the world forward through the power of sport. [S1]

**Q: Where is NIKE, Inc. based?**  
A: NIKE, Inc. is based in Beaverton, Oregon, United States. [S2, S3]

**Q: Which brands are part of NIKE, Inc.?**  
A: NIKE, Inc. includes the Nike, Jordan, and Converse brands. [S2, S3]

**Q: Who founded the business that became Nike?**  
A: Nike's official history identifies Bill Bowerman and Phil Knight as co-founders. Their partnership created Blue Ribbon Sports in 1964. [S4]

**Q: What products does Nike sell?**  
A: Nike sells athletic and sport-inspired footwear, apparel, equipment, and accessories. The exact assortment varies by country, sport, season, and sales channel. [S2, S19]

**Q: Is Nike Membership free?**  
A: Nike describes Membership as free to join. Benefits and availability can vary by country. [S5]

**Q: What is Nike Run Club?**  
A: Nike Run Club is a running app that can support run tracking, goals, guided runs, challenges, and training guidance, depending on current app version and region. [S6]

**Q: What is Nike Training Club?**  
A: Nike Training Club provides workout, training, and wellness-oriented content. Features and availability can vary. [S6]

**Q: What is Nike By You?**  
A: Nike By You is a Member customization experience for selected shoes. Users can choose available colors and materials in a digital builder. [S7]

**Q: How do I find the right Nike size?**  
A: Use the size guide on the exact product page or Nike's official size charts. Select the relevant category and follow its measuring and fit guidance. [S9]

**Q: How can I track a Nike order?**  
A: Members can check order history after signing in. Guests can typically use the order number and purchase email on the official order-status page. This public RAG chatbot itself cannot access Nike orders. [S11]

**Q: Can I change a Nike order after placing it?**  
A: Nike's U.S. help page says orders cannot be edited after placement. A short cancellation window may be available, but this is region-specific and time-sensitive. [S12]

**Q: What is Nike's return window?**  
A: The U.S. policy reviewed on 30 July 2026 stated 60 days for most eligible purchases, with proof of purchase and exceptions. Return periods differ by country and can change. [S13, S14]

**Q: Can Nike shoes go in a washing machine?**  
A: Nike generally does not recommend washing shoes in a washing machine. Hand cleaning with a mild solution and air-drying is preferred. [S17]

**Q: What is Move to Zero?**  
A: Move to Zero is Nike's journey toward zero carbon and zero waste to help protect the future of sport. [S15]

**Q: Can this chatbot check stock or product availability?**  
A: No. This public RAG chatbot has no live inventory access. It can only summarize information stored in the knowledge base.

**Q: Can this chatbot check my Nike order?**  
A: No. The public knowledge workflow cannot access Nike accounts or private Nike order systems. The separate Shopify workflow in this internship project operates only against the project's test commerce backend after verification.

**Q: Can this chatbot process a return or refund?**  
A: No. It can explain public guidance but cannot create a return, issue a refund, or authenticate a Nike account. [S14]

## 16. Recommended Grounding Rules for the RAG Agent

1. Retrieve company context before answering any factual question about Nike.
2. Answer only from retrieved chunks. Do not fill gaps with assumptions.
3. State clearly when a policy is U.S.-specific or time-sensitive.
4. Ask for the user's country before applying shipping, returns, membership, store, contact, or pricing rules.
5. Do not claim access to live inventory, Nike customer accounts, payment systems, delivery carriers, or private Nike order data.
6. Do not ask for passwords, payment-card details, one-time codes, or government identification.
7. When the answer is not present, use the fallback statement and direct the user to the official local Nike Help page.
8. Do not describe the demo as official, affiliated, endorsed, or authorized by NIKE, Inc.

### Suggested system instruction

> You are an unofficial Nike public-information assistant for an educational portfolio demo. For every Nike factual question, use the retrieved knowledge-base context. Do not invent details. Distinguish global company facts from regional policies, ask for the user's country when needed, and clearly say that you cannot access real Nike orders, accounts, inventory, or payment systems.

## 17. Official Source Register

All sources below are official NIKE, Inc. or Nike.com pages. Access and review date: 30 July 2026. Source content can change after this date.

| ID | Official source | URL |
|---|---|---|
| S1 | Nike mission and purpose | https://about.nike.com/en/mission/ |
| S2 | About NIKE, Inc. | https://about.nike.com/en/ |
| S3 | NIKE, Inc. company and headquarters information | https://about.nike.com/en/company |
| S4 | Official history: The Handshake That Started It All | https://about.nike.com/en/magazine/the-handshake-that-started-it-all |
| S5 | Nike Membership benefits | https://www.nike.com/help/a/member-benefits |
| S6 | Nike Training Club and Nike Run Club apps | https://www.nike.com/help/a/ntc-nrc |
| S7 | Nike By You overview | https://www.nike.com/help/a/what-is-nike-by-you |
| S8 | Nike product advice | https://www.nike.com/help/a/product-advice |
| S9 | Nike size and fit guidance | https://www.nike.com/help/a/size-charts |
| S10 | Nike U.S. shipping options | https://www.nike.com/help/a/shipping-delivery |
| S11 | Nike U.S. order tracking | https://www.nike.com/help/a/order-tracking |
| S12 | Nike U.S. order changes and cancellations | https://www.nike.com/help/a/change-cancel-order |
| S13 | Nike U.S. return policy | https://www.nike.com/help/a/returns-policy |
| S14 | Nike U.S. return and exchange process | https://www.nike.com/help/a/how-to-return |
| S15 | Nike sustainability and Move to Zero | https://www.nike.com/Sustainability/ |
| S16 | Nike general shoe-cleaning guidance | https://www.nike.com/a/how-to-clean-shoes |
| S17 | Nike guidance on washing shoes | https://www.nike.com/a/can-you-put-shoes-in-the-washer/ |
| S18 | Nike U.S. shoe and product warranty guidance | https://www.nike.com/help/a/shoe-warranty |
| S19 | NIKE, Inc. fiscal 2026 full-year results | https://investors.nike.com/ |
| S20 | Nike customer service and help topics | https://www.nike.com/help/ |

## 18. Maintenance Notes

- Re-check region-specific policies before public demonstrations or interviews.
- Update the review date whenever shipping, returns, membership, warranty, contact, or financial information is refreshed.
- Re-ingest the full document after material revisions so outdated vector chunks are removed.
- For production use, create separate knowledge bases by country or locale rather than mixing regional policies.
- Keep private order data in a separate authenticated workflow; never store customer order records in this public knowledge corpus.

---

**END OF KNOWLEDGE BASE**
