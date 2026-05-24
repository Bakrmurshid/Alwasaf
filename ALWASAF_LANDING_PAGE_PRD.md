# Product Requirements Document: Alwasaf Landing Page

## 1. Project Overview

Build a complete bilingual landing page for **Alwasaf | الوصف للخدمات الجمركية واللوجستية**, a Saudi customs clearance and logistics company based in Riyadh.

The landing page must present the company as a trustworthy, formal, responsive, and operationally capable partner for customs clearance, logistics, shipping, and goods preparation from the country of origin.

Primary goal:
Convert visitors into leads through WhatsApp, email, or phone contact.

Primary CTA:
تواصل عبر واتساب / Contact on WhatsApp

Primary WhatsApp:
https://wa.me/966555188292

## 2. Business Information

### Company Name
مؤسسة الوصف للتخليص الجمركي

### Brand Display
Alwasaf | الوصف للخدمات الجمركية واللوجستية

### Commercial Details
- Commercial Registration: 1010913425
- License: 4413

### Location
Riyadh, Thulaim District, Saudi Arabia  
الرياض، حي ثليم، المملكة العربية السعودية

### Contact
- Manager / WhatsApp: +966 55 518 8292
- Phone: +966 11 225 5467
- Assistant: +966 50 721 2254
- Email: est@alwasaf.sa
- Website: http://alwasaf.sa/

### Logo Assets
Use the provided logo:
- `logo.jpeg`
- Optional alternative: `logo.png`

## 3. Target Audience

The page is for:
- Factories
- Importers
- Large companies
- Medium companies
- Small companies
- Businesses needing customs clearance across Saudi ports
- Businesses needing logistics, shipping, and goods preparation from country of origin

The audience cares about:
- Fast response
- Fast completion
- Credibility
- Clear communication
- Ability to handle shipments through Saudi sea, land, and air ports
- Operational reliability
- A trained team
- Fleet and logistics support

## 4. Services To Present

### 4.1 Customs Clearance
Arabic copy:
تخليص جمركي عبر المنافذ السعودية البحرية والبرية والجوية، مع متابعة دقيقة للإجراءات والمستندات حتى اكتمال العملية.

English copy:
Customs clearance across Saudi sea, land, and air ports, with accurate follow-up of procedures and documents until completion.

### 4.2 Logistics Services
Arabic copy:
حلول لوجستية تدعم حركة البضائع بعد التخليص، وتساعد العملاء على تنظيم العمليات بكفاءة ووضوح.

English copy:
Logistics solutions that support the movement of goods after clearance and help clients coordinate operations efficiently and clearly.

### 4.3 Shipping
Arabic copy:
تنسيق خدمات الشحن ومتابعة مسار البضائع ضمن عملية منظمة تخدم احتياج العميل ونوع الشحنة.

English copy:
Shipping coordination and shipment follow-up through an organized process tailored to client needs and shipment type.

### 4.4 Goods Preparation From Country of Origin
Arabic copy:
مساندة العملاء في تجهيز البضائع من بلد المنشأ وتنظيم متطلبات الشحن قبل وصولها إلى المنافذ السعودية.

English copy:
Supporting clients with goods preparation from the country of origin and organizing shipping requirements before arrival at Saudi ports.

## 5. Key Differentiators

Show these clearly on the page:

- سرعة التجاوب مع العميل
- سرعة الإنجاز
- المصداقية
- أسطول متكامل
- فريق عمل مدرب
- خدمة جميع المنافذ السعودية: البرية، البحرية، والجوية
- دعم المصانع والمستوردين والشركات الكبيرة والمتوسطة والصغيرة

English equivalents:

- Fast client response
- Fast completion
- Credibility and clarity
- Integrated fleet
- Trained operational team
- Coverage across Saudi land, sea, and air ports
- Support for manufacturers, importers, and companies of all sizes

## 6. Brand Positioning

Position Alwasaf as:

A formal Saudi customs clearance and logistics partner that combines speed, credibility, trained teams, fleet capability, and coverage across all Saudi ports.

Do not position the company as:
- A casual delivery app
- A generic shipping directory
- A global corporation with unverified claims
- A decorative logistics template

## 7. Visual Direction

The page must feel:
- Formal
- Saudi business oriented
- Trustworthy
- Operational
- Clear and structured
- Premium but not flashy
- Modern without losing seriousness

Avoid:
- Purple or blue-purple gradients
- Glassmorphism
- Excessive card grids
- Generic stock SaaS design
- Decorative blobs or abstract shapes
- Claims without evidence
- Overly playful icons or copy

## 8. Design System

### Colors
Use the logo colors as the base.

Suggested tokens:

```css
:root {
  --color-primary: #174679;
  --color-primary-deep: #123963;
  --color-yellow: #ffc61a;
  --color-orange: #f5a313;
  --color-bg: #f7f8f5;
  --color-surface: #fffaf0;
  --color-text: #172333;
  --color-muted: #647080;
  --color-border: #d8dee6;
}
```

Use navy as the main brand color, yellow and orange as accents. Keep the background clean and warm.

### Typography
Recommended:
- Arabic: IBM Plex Sans Arabic, Tajawal, or Cairo
- English: Inter, IBM Plex Sans, or system sans-serif

Requirements:
- Arabic must read well in RTL.
- English must read well in LTR.
- Body text should be comfortable on mobile.
- Avoid very thin font weights.

### Layout
Requirements:
- Mobile-first responsive design
- Arabic default
- RTL layout for Arabic
- LTR layout for English
- Clear header and CTA
- No nested cards
- Sections should be full-width bands or clean constrained layouts
- Use client logos in a clean strip/grid when assets are provided

## 9. Page Structure

### 9.1 Header
Content:
- Logo
- Navigation links:
  - الرئيسية / Home
  - من نحن / About
  - الخدمات / Services
  - المنافذ / Ports
  - العملاء / Clients
  - تواصل معنا / Contact
- Language toggle: عربي / English
- Primary CTA button: تواصل عبر واتساب

Behavior:
- Header remains clean and visible.
- On mobile, use a menu or compact navigation.
- WhatsApp CTA must be visible without hunting.

### 9.2 Hero Section
Arabic headline:
تخليص جمركي ولوجستيات موثوقة عبر جميع المنافذ السعودية

Arabic subheadline:
تدعم مؤسسة الوصف المصانع والمستوردين والشركات في إنجاز إجراءات التخليص الجمركي والشحن والخدمات اللوجستية بسرعة ومصداقية، من بلد المنشأ وحتى اكتمال العملية داخل المملكة.

Primary CTA:
تواصل عبر واتساب

Secondary CTA:
راسلنا عبر البريد

Hero should include:
- Logo or strong brand signal
- Mention of Saudi sea, land, and air ports
- Contact actions
- Visual reference to logistics/customs/ports/fleet, either through a high-quality image or refined visual composition

English headline:
Reliable Customs Clearance and Logistics Across Saudi Ports

English subheadline:
Alwasaf supports manufacturers, importers, and companies with customs clearance, logistics, shipping, and goods preparation from the country of origin, with fast response, clear follow-up, and trained operational teams.

### 9.3 Trust / Coverage Strip
Show three coverage items:
- المنافذ البحرية / Sea Ports
- المنافذ البرية / Land Ports
- المنافذ الجوية / Air Ports

Suggested Arabic text:
نخدم عمليات التخليص والشحن عبر المنافذ السعودية البحرية والبرية والجوية.

### 9.4 About Section
Arabic:
مؤسسة الوصف للتخليص الجمركي هي مؤسسة سعودية مقرها الرياض، تقدم خدمات التخليص الجمركي والخدمات اللوجستية والشحن وتجهيز البضائع من بلد المنشأ. تعمل المؤسسة على خدمة المصانع والمستوردين والشركات الكبيرة والمتوسطة والصغيرة، عبر جميع المنافذ السعودية البحرية والبرية والجوية، من خلال فريق عمل مدرب وأسطول متكامل يساهم في سرعة الإنجاز وجودة المتابعة.

English:
Alwasaf is a Saudi customs clearance and logistics company based in Riyadh. The company provides customs clearance, logistics, shipping, and goods preparation from the country of origin for manufacturers, importers, and companies of all sizes across Saudi sea, land, and air ports. Alwasaf combines trained teams, responsive communication, and an integrated fleet to deliver dependable operational support.

### 9.5 Services Section
Show four service blocks:
1. التخليص الجمركي
2. الخدمات اللوجستية
3. الشحن
4. تجهيز البضائع من بلد المنشأ

Each block should contain:
- Clear icon or visual cue
- Short title
- One concise paragraph
- No excessive copy

### 9.6 Why Alwasaf Section
Show the company strengths:
- سرعة التجاوب
- سرعة الإنجاز
- المصداقية
- أسطول متكامل
- فريق عمل مدرب
- تغطية جميع المنافذ السعودية

Design this as a structured comparison or operational capability section, not a generic repeated-card grid.

### 9.7 Work Process Section
Arabic steps:
1. نستقبل طلب العميل وبيانات الشحنة.
2. نراجع المستندات والمتطلبات حسب نوع البضاعة والمنفذ.
3. نبدأ متابعة إجراءات التخليص والتنسيق التشغيلي.
4. نبقي العميل على اطلاع بمراحل العمل حتى اكتمال العملية.
5. ندعم العميل في الخدمات اللوجستية والشحن حسب الحاجة.

English steps:
1. We receive the client request and shipment details.
2. We review documents and requirements based on shipment type and port.
3. We begin clearance follow-up and operational coordination.
4. We keep the client updated throughout the process.
5. We support logistics and shipping when needed.

### 9.8 Vision and Mission
Arabic vision:
أن تكون مؤسسة الوصف شريكا موثوقا في التخليص الجمركي والخدمات اللوجستية داخل المملكة، من خلال حلول سريعة ومنظمة تدعم نمو أعمال العملاء وتسهّل حركة بضائعهم عبر المنافذ السعودية.

Arabic mission:
نلتزم بتقديم خدمات تخليص جمركي ولوجستية موثوقة تعتمد على سرعة التجاوب، دقة المتابعة، وضوح الإجراءات، وفريق عمل مدرب يساند العميل من بداية العملية حتى اكتمالها.

English vision:
To be a trusted customs clearance and logistics partner in Saudi Arabia, delivering organized and responsive solutions that support business growth and simplify the movement of goods across Saudi ports.

English mission:
To provide dependable customs clearance and logistics services through fast response, accurate follow-up, clear processes, and trained teams that support clients from the start of the operation until completion.

### 9.9 Client Logos Section
Heading Arabic:
عملاء نعتز بخدمتهم

Heading English:
Trusted by Leading Companies

Requirements:
- The company wants to show client logos.
- If real logos are not available yet, create a clean placeholder area that can be replaced later.
- Do not invent client names.
- Do not use fake logos.
- The layout should support 4 to 8 logos.

### 9.10 Contact Section
Arabic heading:
ابدأ الآن مع فريق الوصف

Arabic copy:
تواصل معنا عبر واتساب أو البريد الإلكتروني، وسيقوم فريقنا بمراجعة طلبك والرد عليك بما يناسب نوع الشحنة واحتياجك التشغيلي.

Contact items:
- WhatsApp: +966 55 518 8292
- Phone: +966 11 225 5467
- Assistant: +966 50 721 2254
- Email: est@alwasaf.sa
- Address: الرياض، حي ثليم

CTA buttons:
- تواصل عبر واتساب
- إرسال بريد إلكتروني
- اتصال مباشر

### 9.11 Footer
Must include:

مؤسسة الوصف للتخليص الجمركي  
س.ت: 1010913425 | رخصة: 4413  
الرياض، حي ثليم، المملكة العربية السعودية  
est@alwasaf.sa  
+966 11 225 5467

Legal note:
تخضع إجراءات التخليص الجمركي ومتطلباتها للأنظمة المعمول بها في المملكة العربية السعودية وطبيعة كل شحنة ومستنداتها.

## 10. Bilingual Requirements

The landing page must support Arabic and English.

Default:
- Arabic
- RTL

English mode:
- LTR
- English copy shown

Language toggle:
- Visible in header
- Must switch text and direction
- Must preserve page layout quality in both languages

## 11. Interaction Requirements

### WhatsApp Button
All WhatsApp buttons should open:
https://wa.me/966555188292

Suggested prefilled message:
السلام عليكم، أود الاستفسار عن خدمات التخليص الجمركي واللوجستيات لدى مؤسسة الوصف.

Encoded WhatsApp URL:
https://wa.me/966555188292?text=%D8%A7%D9%84%D8%B3%D9%84%D8%A7%D9%85%20%D8%B9%D9%84%D9%8A%D9%83%D9%85%D8%8C%20%D8%A3%D9%88%D8%AF%20%D8%A7%D9%84%D8%A7%D8%B3%D8%AA%D9%81%D8%B3%D8%A7%D8%B1%20%D8%B9%D9%86%20%D8%AE%D8%AF%D9%85%D8%A7%D8%AA%20%D8%A7%D9%84%D8%AA%D8%AE%D9%84%D9%8A%D8%B5%20%D8%A7%D9%84%D8%AC%D9%85%D8%B1%D9%83%D9%8A%20%D9%88%D8%A7%D9%84%D9%84%D9%88%D8%AC%D8%B3%D8%AA%D9%8A%D8%A7%D8%AA%20%D9%84%D8%AF%D9%89%20%D9%85%D8%A4%D8%B3%D8%B3%D8%A9%20%D8%A7%D9%84%D9%88%D8%B5%D9%81.

### Email Button
Use:
mailto:est@alwasaf.sa

### Phone Button
Use:
tel:+966112255467

## 12. Responsive Requirements

Must work well on:
- Mobile phones
- Tablets
- Desktop screens

Mobile requirements:
- Header must not crowd the logo.
- CTA must remain easy to tap.
- Arabic text must not overflow.
- Service and process sections must stack cleanly.
- Client logo placeholders must remain balanced.

Desktop requirements:
- Hero should feel strong in the first viewport.
- Main CTA should be visible immediately.
- Sections should scan easily.
- Avoid excessive empty space.

## 13. Accessibility Requirements

- Use semantic HTML.
- Use accessible color contrast.
- Provide alt text for logo and images.
- Buttons and links must be keyboard accessible.
- Language and direction attributes must update by language.
- Do not rely on color alone to communicate meaning.

## 14. SEO Requirements

Suggested Arabic title:
مؤسسة الوصف للتخليص الجمركي | تخليص جمركي ولوجستيات في السعودية

Suggested English title:
Alwasaf Customs Clearance and Logistics in Saudi Arabia

Suggested Arabic meta description:
مؤسسة الوصف للتخليص الجمركي تقدم خدمات التخليص الجمركي واللوجستيات والشحن وتجهيز البضائع من بلد المنشأ عبر جميع المنافذ السعودية البحرية والبرية والجوية.

Suggested English meta description:
Alwasaf provides customs clearance, logistics, shipping, and goods preparation from the country of origin across Saudi sea, land, and air ports.

Keywords to naturally include:
- تخليص جمركي
- التخليص الجمركي السعودية
- شركة تخليص جمركي الرياض
- خدمات لوجستية
- شحن
- المنافذ السعودية
- customs clearance Saudi Arabia
- logistics Saudi Arabia

## 15. Content Rules

Do:
- Use formal Arabic.
- Keep copy clear and direct.
- Highlight speed, credibility, team, fleet, and all Saudi ports.
- Use the company details exactly as provided.
- Support client logos without inventing names.

Do not:
- Invent numbers or years of experience.
- Invent client names.
- Claim government affiliation.
- Claim guaranteed clearance.
- Use vague copy such as "best services ever".
- Overload the page with long paragraphs.

## 16. Deliverables

The implementation should produce:

1. A complete landing page.
2. Arabic and English language support.
3. Responsive desktop and mobile layout.
4. Proper usage of provided logo.
5. Contact actions for WhatsApp, email, and phone.
6. Client logo section ready for real logos.
7. Formal visual identity based on navy, yellow, and orange brand colors.
8. Clean footer with registration and license information.

## 17. Acceptance Criteria

The page is complete when:

- The Arabic page loads by default.
- English can be selected and displayed correctly.
- RTL and LTR layouts both work.
- Logo appears clearly.
- WhatsApp CTA opens the correct number.
- Email link opens `est@alwasaf.sa`.
- Phone link uses `+966 11 225 5467`.
- Services are clearly explained.
- Sea, land, and air ports coverage is visible.
- Vision and mission are included.
- Client logo area exists without fake client names.
- Footer includes CR and license numbers.
- The page looks formal, professional, and suitable for a Saudi customs clearance company.
- Mobile layout has no text overlap or broken sections.

## 18. Optional Future Enhancements

Add later when available:

- Real client logos
- Real office or fleet photos
- Testimonials
- Shipment request form
- Document upload form
- Google Maps embed for Riyadh, Thulaim
- Analytics events for WhatsApp, phone, and email clicks
- Additional landing pages for specific services such as customs clearance, logistics, and shipping

