rest-express@1.0.0 dev
> NODE_ENV=development tsx server/index.ts

Initializing Google Drive service...
Found existing app root folder: 1ZKyJIKgXdY7bCvLxLIaYoXWIx31nQfYd
Google Drive service initialized successfully
Initialized AI provider from database: openai
2:39:01 PM [express] serving on port 5000
Starting to seed categories...
Category Income already exists
Category Shopping already exists
Category Food & Drink already exists
Category Groceries already exists
Category Housing already exists
Category Transportation already exists
Category Entertainment already exists
Category Utilities already exists
Category Healthcare already exists
Category Insurance already exists
Category Savings already exists
Category Education already exists
Category Investments already exists
Category Other already exists
Categories seeding completed successfully
2:39:02 PM [express] Categories seeded successfully
Starting to seed credit packages...
Credit package Starter Pack already exists
Credit package Basic Pack already exists
Credit package Premium Pack already exists
Credit package Enterprise Pack already exists
Credit packages seeding completed successfully
2:39:02 PM [express] Credit packages seeded successfully
Browserslist: browsers data (caniuse-lite) is 8 months old. Please run:
  npx update-browserslist-db@latest
  Why you should do it regularly: https://github.com/browserslist/update-db#readme
2:39:06 PM [express] GET /api/user 401 in 3ms :: {"isAuthenticated":false}
2:39:08 PM [express] GET /api/user 401 in 1ms :: {"isAuthenticated":false}
2:39:10 PM [express] GET /api/user 401 in 1ms :: {"isAuthenticated":false}
2:39:24 PM [express] POST /api/login 200 in 366ms :: {"id":3,"username":"ickhatib","email":"info@act…
2:39:27 PM [express] GET /api/user 200 in 60ms :: {"isAuthenticated":true,"user":{"id":3,"username":…
2:39:27 PM [express] GET /api/credit-packages 304 in 120ms :: [{"id":1,"name":"Starter Pack","descri…
AI OCR extraction method selected (default)
Using extraction method: ai_ocr
Uploading file to Google Drive for user 3
Creating Google Drive folder for user: ickhatib
Uploaded file to Google Drive: 1n9lwKNl1eHpqkYCi_UdjJ63WfkmVNyPN
File uploaded to Google Drive: 1n9lwKNl1eHpqkYCi_UdjJ63WfkmVNyPN
File backup status: Successfully backed up to Google Drive
Starting PDF processing for document #127: {
  filePath: 'uploads/pdfs/user_3/1749393590088_StarlingStatement_10-10-2024_31-03-2025.pdf',
  extractionMethod: 'ai_ocr',
  timestamp: '2025-06-08T14:39:52.180Z'
}
2:39:52 PM [express] POST /api/upload 202 in 2661ms :: {"message":"File uploaded and processing star…
Processing PDF file: StarlingStatement_10-10-2024_31-03-2025.pdf
Processing PDF with 3 pages
Processing page 1 with OCR mode (text content not needed)
Processing page 1 of 3
Extraction method evaluation: 'ai_ocr' === 'ai_ocr' is true
Extraction method type: string
String comparison: 'ai_ocr' === 'ai_ocr' is true
Using AI OCR vision-based extraction for page 1 - TAKING OCR BRANCH
Processing vision-based analysis on file: uploads/pdfs/user_3/1749393590088_StarlingStatement_10-10-2024_31-03-2025.pdf, page: 1
Using Landing.ai vision API for OCR extraction from StarlingStatement_10-10-2024_31-03-2025.pdf page 1
Using full PDF for Landing.ai OCR analysis
Starting OCR extraction with Landing.ai for PDF page 1
Vision data size: 214416 characters
Using Landing.ai for OCR vision analysis
Using Landing.ai Agentic Document Extraction for financial data extraction
2:39:52 PM [express] GET /api/documents/127/status 200 in 120ms :: {"id":127,"userId":3,"filename":"…
2:39:55 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:39:57 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:39:59 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:02 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:04 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:06 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:08 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:40:11 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:13 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:15 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:18 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:20 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:40:22 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:40:24 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:27 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:40:29 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:31 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:40:33 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:36 PM [express] GET /api/documents/127/status 304 in 128ms :: {"id":127,"userId":3,"filename":"…
2:40:38 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
Landing.ai API response received
Landing.ai API response structure: [ 'data', 'errors', 'extraction_error' ]
Parsed data structure: [ 'markdown', 'chunks', 'extracted_schema', 'extraction_metadata' ]
Has markdown: true
Has chunks: true Count: 27
Landing.ai extracted markdown content length: 24664
Using OpenAI to analyze Landing.ai extracted text
ICK ------------------------------------------------------------------------------
logo: Starling Bank

Visible Elements : 
  • Circular purple icon with a stylized white "S" shape inside.
  • To the right, the text "Starling Bank" in dark blue, sans-serif font, with "Starling" above "Bank".
  • No tagline or additional text present.
  • Logo is horizontally aligned, icon left, text right.

Dimensions & Placement : 
  • Icon is approximately the same height as the two lines of text.
  • Text is left-aligned with the icon.

Analysis : 
  • The logo uses a simple, modern design with a cool colour palette, suggesting a digital-first, contemporary banking brand. <!-- figure, from page 0 (l=0.041,t=0.027,r=0.245,b=0.080), with ID e398d68e-eb0d-4486-af6a-e0079e30d001 -->

Summary : This is a circular stamp featuring the Starling Bank logo, the words "TRUE COPY", a date, and a reference number.

stamp:  
Shape & Border :  
  • Circular stamp with a dotted border.  

Text & Graphic Elements :  
  • Central logo: stylised "S" in a dark circle.  
  • Central text: "Starling Bank" in two lines, bold sans-serif font.  
  • Outer ring text (clockwise from top):  
    – "TRUE COPY"  
    – "03-05-2023" (date)  
    – "TRUE COPY"  
    – "8345493503" (reference number)  

Ink Colour & Orientation :  
  • All elements in dark blue.  
  • Upright orientation; text evenly spaced around the circle.  

Dimensions & Placement :  
  • Proportions suggest a standard digital stamp, suitable for document authentication.  

Analysis :  
  • The stamp is designed to certify a document as a "true copy" from Starling Bank, with a unique reference number and date for traceability. <!-- figure, from page 0 (l=0.447,t=0.026,r=0.550,b=0.095), with ID 1ff20ef9-1597-4e88-a5fb-9d4a1e972b80 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.644,t=0.032,r=0.957,b=0.066), with ID 25f138d5-9b2e-4e3c-8339-b2942f8a155c -->

Prestige Civils Limited  
71-75 Shelton Street  
Covent Garden  
London  
WC2H 9JQ <!-- text, from page 0 (l=0.045,t=0.109,r=0.271,b=0.188), with ID 42bbdf62-c268-472a-aab7-fac7da93e721 -->

Summary: 10/10/2024 - 31/03/2025

Opening Balance: £19957.82
Payments In: £63086.08
Payments Out: £23837.39
Closing Balance: £59206.51 <!-- text, from page 0 (l=0.516,t=0.106,r=0.945,b=0.249), with ID d00de5d5-e996-4dce-9476-c42373f5fce8 -->

Account Name: Prestige Civils Limited
IBAN: GB17SRLG60837152721928
BIC: SRLGGB2L
Sort code: 60-83-71
Account Number: 52721928 <!-- text, from page 0 (l=0.043,t=0.203,r=0.483,b=0.279), with ID e062b38e-81ac-48be-ab37-44872cc6cc52 -->

Summary : This is a logo and certification mark indicating that deposits are protected by the Financial Services Compensation Scheme (FSCS).

logo: FSCS Protected and eligibility statement

Logo Elements : 
  • Stylised "fscs" in purple with an oval outline.
  • The word "Protected" appears below the logo in smaller text.

Text Content : 
  • "Your deposit is eligible for protection by the Financial Services Compensation Scheme."

Placement & Design : 
  • Logo is positioned to the left of the text.
  • Text is in a sans-serif font, black colour, left-aligned.
  • White background.

Analysis : 
  • The logo and accompanying text communicate that the associated financial product is covered by the FSCS, reassuring customers about deposit protection. <!-- figure, from page 0 (l=0.516,t=0.252,r=0.879,b=0.297), with ID 266cd7af-b462-4277-8c97-48568b1f6475 -->

10/10/2024 - 31/03/2025 Statement <!-- text, from page 0 (l=0.046,t=0.318,r=0.451,b=0.342), with ID 6a6b4465-c7b1-4dfc-983e-6fa98a8663c1 -->

<table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table> <!-- table, from page 0 (l=0.042,t=0.352,r=0.957,b=0.898), with ID 0334fc78-ba4e-412a-836e-bd0eaa424241 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.938), with ID 67071bb4-a21f-4552-9ebc-fb8a461e63a3 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.045,t=0.947,r=0.938,b=0.988), with ID e0cb14ec-e081-4700-9de9-4143b69c5176 -->

1 <!-- marginalia, from page 0 (l=0.931,t=0.978,r=0.943,b=0.987), with ID 439c9279-5a95-4b2f-b9ba-83287eb11da7 -->

logo: Starling Bank

• The image displays the logo of Starling Bank.
• The logo consists of a solid purple circle containing a stylized white "S" shape, positioned to the left of the text.
• The text "Starling Bank" appears in a bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" directly below it, both left-aligned.
• The overall design is clean and modern, with a simple colour palette of purple, white, and dark blue.
• No additional taglines, icons, or graphical elements are present.

Analysis :
• The logo uses a minimalist design and a distinctive purple colour, likely aiming to convey a modern, trustworthy, and digital-first brand identity. <!-- figure, from page 0 (l=0.042,t=0.028,r=0.243,b=0.079), with ID 68c42b83-f4da-450c-8fbc-1a9ac7226e83 -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a date and reference number.

stamp:  
Shape & Border : 
  • Circular stamp with a dotted border.
  • Text "TRUE COPY" repeated twice along the upper and lower arcs of the border.

Text & Graphic Elements : 
  • Central logo: stylized "S" in a dark blue circle.
  • "Starling Bank" written in bold, dark blue, centered below the logo.
  • Date: "03-05-2023" on the right side of the border.
  • Reference number: "B354693503" on the left side of the border.

Ink Colour & Orientation : 
  • All elements in dark blue ink.
  • Upright orientation; text and logo are horizontally aligned.

Dimensions & Placement Cues : 
  • Proportions suggest a small, standard stamp size (exact dimensions not specified).
  • Logo and text are centered within the circular border.

Analysis : 
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a specific date and reference number for traceability. The use of a circular design and consistent dark blue branding reinforces authenticity and corporate identity. <!-- figure, from page 0 (l=0.449,t=0.026,r=0.548,b=0.093), with ID b1b74548-0488-4f0a-9df4-6fe85e95a5ee -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.645,t=0.032,r=0.957,b=0.066), with ID 14b94500-201b-4bb9-bd12-92b44372bdf0 -->

<table><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-35-45627)</td><td>£2250.00</td><td></td></tr><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£20823.00</td></tr><tr><td>12/12/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£122.80</td><td></td></tr><tr><td>12/12/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£20652.20</td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-36-45634)</td><td>£2250.00</td><td></td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22702.20</td></tr><tr><td>14/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22602.20</td></tr><tr><td>15/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22502.20</td></tr><tr><td>16/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£22302.20</td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-37-45641)</td><td>£2250.00</td><td></td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£24052.20</td></tr><tr><td>21/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23852.20</td></tr><tr><td>22/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23652.20</td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td></td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23252.20</td></tr><tr><td>25/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£22952.20</td></tr><tr><td>26/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td><td>£22552.20</td></tr><tr><td>30/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£22052.20</td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (DEC 24 - Salary)</td><td>£1095.00</td><td></td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (DEC 24 - Salary)</td><td>£1047.50</td><td>£19909.70</td></tr><tr><td>08/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£86.55</td><td>£19823.15</td></tr><tr><td>10/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£56.52</td><td></td></tr><tr><td>10/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-40-45641)</td><td>£2250.00</td><td>£22016.63</td></tr><tr><td>13/01/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£146.61</td><td>£21870.02</td></tr><tr><td>14/01/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£21822.02</td></tr><tr><td>17/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-41-45669)</td><td>£2250.00</td><td>£24072.02</td></tr><tr><td>18/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23872.02</td></tr><tr><td>24/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-42-45676)</td><td>£2250.00</td><td>£26122.02</td></tr><tr><td>31/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-43-45683)</td><td>£2025.00</td><td>£28147.02</td></tr><tr><td>02/02/2025</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td>£1.74</td><td></td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (JAN 25 - Salary)</td><td>£1047.50</td><td></td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (JAN 25 - Salary)</td><td>£1047.50</td><td>£26050.28</td></tr><tr><td>03/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£26.98</td><td></td></tr><tr><td>03/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£445.00</td><td>£25578.30</td></tr><tr><td>05/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£52.25</td><td>£25626.05</td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-44-45690)</td><td>£2250.00</td><td></td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td><td></td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£27276.05</td></tr><tr><td>08/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£26976.05</td></tr><tr><td>12/02/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£108.93</td><td></td></tr><tr><td>12/02/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£26819.12</td></tr><tr><td>14/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-45-45697)</td><td>£2250.00</td><td>£29069.12</td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£80.00</td><td>£28889.12</td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-46-45704)</td><td>£2250.00</td><td></td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30839.12</td></tr><tr><td>22/02/2025</td><td>CHIP & PIN</td><td>Currys</td><td>£122.00</td><td></td></tr><tr><td>24/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£70.00</td><td>£30647.12</td></tr><tr><td>25/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£194.10</td><td>£30453.02</td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30053.02</td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-47-45711)</td><td>£2700.00</td><td></td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (FEB 25 - Salary)</td><td>£1047.50</td><td></td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (FEB 25 - Salary)</td><td>£1047.50</td><td>£30658.02</td></tr></table> <!-- table, from page 0 (l=0.041,t=0.107,r=0.959,b=0.898), with ID 6ec5e2b3-34d0-429b-8a60-23314300b34a -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.043,t=0.906,r=0.946,b=0.938), with ID d2c79d4e-cc4e-43d7-a5ea-74fde61d95e1 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.046,t=0.947,r=0.927,b=0.987), with ID b201e0c3-876d-4aa5-ad33-8eca180872fa -->

2 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID 1575a4c8-81af-449d-aae7-5106a437b0b4 -->

logo: Starling Bank

Summary : This image displays the logo of Starling Bank, a UK-based digital bank.

Logo Elements : 
  • Circular purple icon on the left with a stylized white "S" shape in the center.
  • To the right of the icon, the text "Starling Bank" appears in bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" below it.
  • The logo uses a clean, modern design with a simple color palette of purple, white, and dark blue.

Dimensions & Placement : 
  • The icon and text are horizontally aligned, with the icon on the left and the text on the right.
  • The icon is approximately the same height as the two lines of text combined.

Analysis : 
  • The logo’s use of a stylized "S" and modern typography conveys a sense of simplicity and digital innovation, aligning with Starling Bank’s branding as a technology-driven financial institution. <!-- figure, from page 0 (l=0.041,t=0.028,r=0.244,b=0.079), with ID ada98e4e-f1fe-4cd7-be15-ee3fc2010e3b -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a date and reference number.

stamp:  
Shape & Border :  
  • Circular stamp with a dotted border.

Ink Colour :  
  • Dark blue ink.

Text :  
  • "TRUE COPY" appears twice, at the top and bottom of the circle.
  • "Starling Bank" is centered in the middle, with the Starling Bank logo above the text.
  • Date: "02-05-2025" appears on the right side of the circle.
  • Reference number: "3356493503" appears on the left side of the circle.

Graphic Elements :  
  • Starling Bank logo (stylized "S" in a circle) above the bank name.

Orientation :  
  • All text is upright and evenly spaced around the circle.

Analysis :  
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a specific date and reference number for verification. <!-- figure, from page 0 (l=0.448,t=0.025,r=0.548,b=0.094), with ID e851236f-c709-4ac2-a013-360287e84cc5 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- marginalia, from page 0 (l=0.645,t=0.032,r=0.957,b=0.067), with ID 27f5a248-ebd9-45de-aba3-f242736cae74 -->

<table><tbody><tr><td>04/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (VAT Backdate)</td><td>£18434.39</td><td>£49092.41</td></tr><tr><td>07/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-48-45718)</td><td>£2700.00</td><td>£51792.41</td></tr><tr><td>12/03/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£108.93</td><td></td></tr><tr><td>12/03/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£51635.48</td></tr><tr><td>14/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-49-45725)</td><td>£2700.00</td><td>£54335.48</td></tr><tr><td>18/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£110.59</td><td>£54224.89</td></tr><tr><td>21/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-50-45732)</td><td>£2700.00</td><td>£56924.89</td></tr><tr><td>24/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£87.77</td><td>£56837.12</td></tr><tr><td>25/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£35.00</td><td></td></tr><tr><td>25/03/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£240.00</td><td>£56562.12</td></tr><tr><td>26/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£55.61</td><td>£56506.51</td></tr><tr><td>28/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-51-45739)</td><td>£2700.00</td><td>£59206.51</td></tr></tbody></table> <!-- table, from page 0 (l=0.042,t=0.107,r=0.956,b=0.286), with ID 695b2923-ea49-4c17-9bcd-0b74df0c334a -->

We charge interest each day you are overdrawn. We calculate interest on your end of day account balance. For further information about our interest rates, refer to www.starlingbank.com/legal
Date range applicable: 10/10/2024 - 31/03/2025
<table><thead><tr><th>Interest rate paid on Account Balance</th><th>%AER Variable</th><th>%Gross Variable</th><th>Interest rate charged on Account Balance</th><th>%EAR Variable</th></tr></thead><tbody><tr><td>£0.00 - unlimited</td><td>0.00%</td><td>0.00%</td><td>Less than £0</td><td>0.00%</td></tr></tbody></table> <!-- table, from page 0 (l=0.043,t=0.292,r=0.955,b=0.369), with ID ac946800-83a5-4827-8509-88241238fbb4 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.939), with ID 2ffde447-97ea-4ccb-a5c9-8cff146dd4ce -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- marginalia, from page 0 (l=0.045,t=0.947,r=0.935,b=0.988), with ID 7af7bd08-b5f5-47b2-98c1-a0d8b8905c37 -->

3 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID 604a7d19-e1ad-4ef7-a53a-63aeba2972ef -->
-----------------------------I-------------------------------------------------ICK
ICK --- Using Landing.ai text-based extraction with OpenAI processing
ICK 2 ------------------------------------------------------------------------------
Extracted table content: <table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table>
-----------------------------I-------------------------------------------------ICK 2
2:40:40 PM [express] GET /api/documents/127/status 304 in 121ms :: {"id":127,"userId":3,"filename":"…
2:40:42 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:40:45 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:47 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:40:49 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
OpenAI raw response: {
  "transactions": [
    {
      "date": "2024-10-11",
      "description": "CARMICHAEL UK",
      "amount": 2066.68,
      "category": "Income",
      "balance": 22024.50
    },
    {
      "date": "2024-10-14",
      "description": "EE",
      "amount": -227.10,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-10-14",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 21777.40
    },
    {
      "date": "2024-10-17",
      "description": "Tahwa Palusi Bowden",
      "amount": -1000.00,
      "category": "Investments",
      "balance": 20777.40
    },
    {
      "date": "2024-10-18",
      "description": "CARMICHAEL UK",
      "amount": 1520.01,
      "category": "Income",
      "balance": 22297.41
    },
    {
      "date": "2024-10-21",
      "description": "Tahwa Palusi Bowden",
      "amount": -300.00,
      "category": "Investments",
      "balance": 21997.41
    },
    {
      "date": "2024-10-25",
      "description": "Tahwa Palusi Bowden",
      "amount": -400.00,
      "category": "Investments",
      "balance": 21597.41
    },
    {
      "date": "2024-11-05",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-11-05",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": 19502.41
    },
    {
      "date": "2024-11-06",
      "description": "Trainline",
      "amount": -29.92,
      "category": "Transportation",
      "balance": 19472.49
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -2000.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -500.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Trainline",
      "amount": -41.49,
      "category": "Transportation",
      "balance": 16931.00
    },
    {
      "date": "2024-11-08",
      "description": "Trainline",
      "amount": -76.60,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-08",
      "description": "Currys",
      "amount": -147.98,
      "category": "Shopping",
      "balance": 16706.42
    },
    {
      "date": "2024-11-09",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 16606.42
    },
    {
      "date": "2024-11-12",
      "description": "EE",
      "amount": -148.57,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Wifi",
      "amount": -5.00,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 16432.85
    },
    {
      "date": "2024-11-13",
      "description": "Trainline",
      "amount": -59.35,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-13",
      "description": "Tahwa Palusi Bowden",
      "amount": -306.00,
      "category": "Investments",
      "balance": 16067.50
    },
    {
      "date": "2024-11-15",
      "description": "Tahwa Palusi Bowden",
      "amount": -260.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -26.47,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -20.08,
      "category": "Transportation",
      "balance": 15760.95
    },
    {
      "date": "2024-11-16",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 15660.95
    },
    {
      "date": "2024-11-22",
      "description": "CARMICHAEL UK",
      "amount": 3040.00,
      "category": "Income",
      "balance": 18700.95
    },
    {
      "date": "2024-11-27",
      "description": "Trainline",
      "amount": -45.45,
      "category": "Transportation",
      "balance": 18655.50
    },
    {
      "date": "2024-11-28",
      "description": "Trainline",
      "amount": -54.78,
      "category": "Transportation",
      "balance": 18600.72
    },
    {
      "date": "2024-11-29",
      "description": "CARMICHAEL UK",
      "amount": 2250.00,
      "category": "Income",
      "balance": 20850.72
    },
    {
      "date": "2024-12-01",
      "description": "Trainline",
      "amount": -41.91,
      "category": "Transportation",
      "balance": 20808.81
    },
    {
      "date": "2024-12-02",
      "description": "1stformations",
      "amount": -1.74,
      "category": "Other",
      "balance": null
    },
    {
      "date": "2024-12-02",
      "description": "Trainline",
      "amount": -39.07,
      "category": "Transportation",
      "balance": 20768.00
    },
    {
      "date": "2024-12-03",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-12-03",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": 18673.00
    }
  ],
  "summary": {
    "totalIncome": 8876.69,
    "totalExpenses": 10189.61,
    "netChange": -1312.92
  }
}
Landing.ai + OpenAI extraction completed: 34 transactions found
Landing.ai OCR extraction complete for page 1 with 34 transactions extracted
Summary: Income: 8876.69, Expenses: 10189.61, Net: -1312.92
Extracted 34 transactions from page 1
Processing page 2 with OCR mode (text content not needed)
Processing page 2 of 3
Extraction method evaluation: 'ai_ocr' === 'ai_ocr' is true
Extraction method type: string
String comparison: 'ai_ocr' === 'ai_ocr' is true
Using AI OCR vision-based extraction for page 2 - TAKING OCR BRANCH
Processing vision-based analysis on file: uploads/pdfs/user_3/1749393590088_StarlingStatement_10-10-2024_31-03-2025.pdf, page: 2
Using Landing.ai vision API for OCR extraction from StarlingStatement_10-10-2024_31-03-2025.pdf page 2
Using full PDF for Landing.ai OCR analysis
Starting OCR extraction with Landing.ai for PDF page 2
Vision data size: 214416 characters
Using Landing.ai for OCR vision analysis
Using Landing.ai Agentic Document Extraction for financial data extraction
2:40:52 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:54 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:56 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:40:59 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:41:01 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:41:03 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:05 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:41:08 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:41:10 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:12 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:41:15 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:41:17 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:19 PM [express] GET /api/documents/127/status 304 in 121ms :: {"id":127,"userId":3,"filename":"…
2:41:21 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:24 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:41:26 PM [express] GET /api/documents/127/status 304 in 120ms :: {"id":127,"userId":3,"filename":"…
2:41:28 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:41:31 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:33 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:41:35 PM [express] GET /api/documents/127/status 304 in 125ms :: {"id":127,"userId":3,"filename":"…
2:41:37 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
Landing.ai API response received
Landing.ai API response structure: [ 'data', 'errors', 'extraction_error' ]
Parsed data structure: [ 'markdown', 'chunks', 'extracted_schema', 'extraction_metadata' ]
Has markdown: true
Has chunks: true Count: 27
Landing.ai extracted markdown content length: 24791
Using OpenAI to analyze Landing.ai extracted text
ICK ------------------------------------------------------------------------------
logo: Starling Bank

Visible Elements : 
  • Circular purple icon with a stylized white "S" shape inside.
  • To the right, the text "Starling Bank" in dark blue, with "Starling" on the first line and "Bank" on the second line.
  • Sans-serif font, all text left-aligned.
  • No tagline or additional symbols present.

Dimensions & Placement : 
  • Icon is approximately the same height as the two lines of text.
  • Icon is placed to the left of the text, with moderate spacing.

Analysis : 
  • The logo uses a simple, modern design with a distinctive icon and clear, bold text, likely aiming for a contemporary and trustworthy brand image. <!-- figure, from page 0 (l=0.041,t=0.027,r=0.245,b=0.080), with ID 083c1245-aed8-4900-9aa9-a70251214386 -->

Summary : This is a circular stamp indicating a "True Copy" certification from Starling Bank, dated 03-05-2023, with a unique reference number.

stamp: circular "True Copy" certification from Starling Bank

Shape & Border :
  • Circular stamp with dotted border.
  • Text arranged around the circumference.

Ink Colour :
  • Dark blue ink.

Text & Graphic Elements :
  • Central logo: stylised "S" in a dark blue circle.
  • "Starling Bank" in bold, sans-serif font, centered.
  • Circumferential text (clockwise from top): "TRUE COPY · 03-05-2023 · TRUE COPY · 8345493503".
  • All text in uppercase except the reference number.

Date & Reference :
  • Date: 03-05-2023.
  • Reference number: 8345493503.

Orientation & Placement :
  • Logo and text are upright and centered within the circle.

Analysis :
  • The stamp certifies a document as a true copy, with clear branding and a unique identifier for traceability. <!-- figure, from page 0 (l=0.447,t=0.026,r=0.550,b=0.095), with ID 6d91f995-4315-47b2-a777-2a7a4f14b858 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.644,t=0.032,r=0.957,b=0.066), with ID 28f95238-8dc4-40b3-ad74-e42a98e1e8a2 -->

Prestige Civils Limited
71-75 Shelton Street
Covent Garden
London
WC2H 9JQ <!-- text, from page 0 (l=0.045,t=0.109,r=0.271,b=0.188), with ID 24542168-5cc2-43d1-ab6d-07c789ec6642 -->

Summary: 10/10/2024 - 31/03/2025

Opening Balance: £19957.82
Payments In: £63086.08
Payments Out: £23837.39
Closing Balance: £59206.51 <!-- text, from page 0 (l=0.516,t=0.106,r=0.945,b=0.249), with ID 79c878ff-0c93-4778-9596-3734e9aaddbe -->

Account Name: Prestige Civils Limited
IBAN: GB17SRLG60837152721928
BIC: SRLGGB2L
Sort code: 60-83-71
Account Number: 52721928 <!-- text, from page 0 (l=0.043,t=0.203,r=0.483,b=0.279), with ID 2e43e8a5-71d0-4370-b82b-a626091b8444 -->

Summary : This image is a logo and certification mark indicating that deposits are protected by the Financial Services Compensation Scheme (FSCS).

logo: FSCS Protected, Financial Services Compensation Scheme
  Scene Overview :
    • The image features the FSCS logo, which consists of stylized lowercase letters "fscs" in purple, encircled by a partial oval.
    • The word "Protected" appears below the logo in smaller purple text.
    • To the right, the text reads: "Your deposit is eligible for protection by the Financial Services Compensation Scheme."
  Technical Details :
    • The logo and text are presented on a white background.
    • All text is in a sans-serif font.
    • The logo is positioned to the left, with the explanatory text aligned to the right.
  Spatial Relationships :
    • The logo and "Protected" text are grouped together on the left, with the main message occupying the majority of the horizontal space to the right.
  Analysis :
    • The logo and accompanying text communicate that the associated financial product is covered by the FSCS, providing reassurance of deposit protection to customers. <!-- figure, from page 0 (l=0.516,t=0.252,r=0.879,b=0.297), with ID 389e858d-b7b8-4c12-bd8e-69b41b49d09a -->

10/10/2024 - 31/03/2025 Statement <!-- text, from page 0 (l=0.046,t=0.318,r=0.451,b=0.342), with ID f81a2392-9b10-4340-87e5-84f4a8e2162a -->

<table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table> <!-- table, from page 0 (l=0.042,t=0.352,r=0.957,b=0.898), with ID e4bd4514-cea8-4c1d-b9eb-8369f19543fc -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.938), with ID 1b075d96-c8ca-4e74-9744-309ac9354da4 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.045,t=0.947,r=0.938,b=0.988), with ID 68daa915-be54-4c5f-a8ba-f9b642141617 -->

1 <!-- marginalia, from page 0 (l=0.931,t=0.978,r=0.943,b=0.987), with ID c2304b35-b489-42a2-a1fa-7d2e6346f60c -->

logo: Starling Bank

• The image displays the logo of Starling Bank.
• The logo consists of a solid purple circle containing a stylized white "S" shape.
• To the right of the circle, the words "Starling Bank" are written in a bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" below it.
• The design is simple, modern, and uses a limited colour palette of purple, white, and dark blue.
• There are no taglines, additional symbols, or fine print visible.

Analysis :
• The logo uses a clean, minimalist design with a distinctive "S" mark, likely intended to convey modernity and trustworthiness in the banking sector. <!-- figure, from page 0 (l=0.042,t=0.028,r=0.243,b=0.079), with ID 4181d80b-967d-4e61-93ea-5cf1fb778d51 -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a date and a reference number.

stamp:  
Shape & Border :  
  • Circular stamp with a dotted border.  

Text & Graphic Elements :  
  • Central logo: stylised "S" in a dark blue circle.  
  • Main text: "Starling Bank" in bold, dark blue, centred below the logo.  
  • Outer ring text (clockwise from top):  
    – "TRUE COPY"  
    – "03-05-2023" (date)  
    – "TRUE COPY"  
    – "B354693503" (reference number)  

Ink Colour :  
  • All elements in dark blue.  

Orientation & Dimensions :  
  • Upright orientation; proportions suggest a near-perfect circle.  
  • No explicit size or scale provided.  

Analysis :  
  • The stamp certifies a document as a "True Copy" from Starling Bank, dated 03-05-2023, with a unique reference number for traceability. <!-- figure, from page 0 (l=0.449,t=0.026,r=0.548,b=0.093), with ID 855ea47e-ca1b-40d2-9586-480b9da2a5a1 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.645,t=0.032,r=0.957,b=0.066), with ID 0ccc3805-d4ce-420a-9773-0d5d26c6e1da -->

<table><thead><tr><th>Date</th><th>Transaction Type</th><th>Description</th><th>Amount</th><th>Balance</th></tr></thead><tbody><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-35-45627)</td><td>£2250.00</td><td></td></tr><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£20823.00</td></tr><tr><td>12/12/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£122.80</td><td></td></tr><tr><td>12/12/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£20652.20</td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-36-45634)</td><td>£2250.00</td><td></td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22702.20</td></tr><tr><td>14/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22602.20</td></tr><tr><td>15/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22502.20</td></tr><tr><td>16/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£22302.20</td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-37-45641)</td><td>£2250.00</td><td></td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£24052.20</td></tr><tr><td>21/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23852.20</td></tr><tr><td>22/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23652.20</td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td></td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23252.20</td></tr><tr><td>25/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£22952.20</td></tr><tr><td>26/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td><td>£22552.20</td></tr><tr><td>30/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£22052.20</td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (DEC 24 - Salary)</td><td>£1095.00</td><td></td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (DEC 24 - Salary)</td><td>£1047.50</td><td>£19909.70</td></tr><tr><td>08/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£86.55</td><td>£19823.15</td></tr><tr><td>10/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£56.52</td><td></td></tr><tr><td>10/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-40-45641)</td><td>£2250.00</td><td>£22016.63</td></tr><tr><td>13/01/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£146.61</td><td>£21870.02</td></tr><tr><td>14/01/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£21822.02</td></tr><tr><td>17/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-41-45669)</td><td>£2250.00</td><td>£24072.02</td></tr><tr><td>18/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23872.02</td></tr><tr><td>24/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-42-45676)</td><td>£2250.00</td><td>£26122.02</td></tr><tr><td>31/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-43-45683)</td><td>£2025.00</td><td>£28147.02</td></tr><tr><td>02/02/2025</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td>£1.74</td><td></td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (JAN 25 - Salary)</td><td>£1047.50</td><td></td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (JAN 25 - Salary)</td><td>£1047.50</td><td>£26050.28</td></tr><tr><td>03/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£26.98</td><td></td></tr><tr><td>03/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£345.00</td><td>£25678.30</td></tr><tr><td>05/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£52.25</td><td>£25626.05</td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-44-45690)</td><td>£2250.00</td><td></td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td><td></td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£27276.05</td></tr><tr><td>08/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£26976.05</td></tr><tr><td>12/02/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£108.93</td><td></td></tr><tr><td>12/02/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£26819.12</td></tr><tr><td>14/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-45-45697)</td><td>£2250.00</td><td>£29069.12</td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£80.00</td><td>£28889.12</td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-46-45704)</td><td>£2250.00</td><td></td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30839.12</td></tr><tr><td>22/02/2025</td><td>CHIP & PIN</td><td>Currys</td><td>£122.00</td><td></td></tr><tr><td>24/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£70.00</td><td>£30647.12</td></tr><tr><td>25/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£194.10</td><td>£30453.02</td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td></td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30053.02</td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-47-45711)</td><td>£2700.00</td><td></td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (FEB 25 - Salary)</td><td>£1047.50</td><td></td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (FEB 25 - Salary)</td><td>£1047.50</td><td>£30658.02</td></tr></tbody></table> <!-- table, from page 0 (l=0.041,t=0.107,r=0.959,b=0.898), with ID c73b84d7-c672-47f8-8a0f-f7bc12506cc8 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.043,t=0.906,r=0.946,b=0.938), with ID d953d903-38dc-49d7-acd0-a6d7cef29139 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.046,t=0.947,r=0.927,b=0.987), with ID debec5de-fd4f-434e-95f5-7d410beebcf0 -->

2 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID a5d7fd0c-eb86-4c1b-9746-f53c3c628b02 -->

logo: Starling Bank

• The image displays the logo of Starling Bank.
• The logo consists of a solid purple circle containing a stylized white "S" shape, positioned to the left of the text.
• The text "Starling Bank" appears in bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" directly below it, left-aligned.
• The overall design is clean and modern, with a simple colour palette of purple, white, and dark blue.
• No additional taglines, icons, or graphical elements are present.

Analysis :
• The logo uses a minimalist design and a distinctive purple colour, likely aiming to convey a modern, trustworthy, and digital-first brand identity. <!-- figure, from page 0 (l=0.041,t=0.028,r=0.244,b=0.079), with ID dd5ea072-be5c-4d3d-9867-eb5a3a3afb42 -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a specific date and reference number.

stamp: 
Shape & Border : 
  • Circular stamp with a dotted border.
  • Blue ink.

Text & Graphic Elements : 
  • Central logo: stylised "S" in a dark blue circle.
  • Central text: "Starling Bank" in two lines, bold sans-serif font.
  • Outer ring text (clockwise from top): "TRUE COPY", "02-05-2025", "TRUE COPY", "3356493503".
  • All text in uppercase except the reference number.

Date & Reference : 
  • Date: "02-05-2025" (likely 2nd May 2025, format not specified).
  • Reference number: "3356493503".

Orientation & Placement : 
  • All elements are horizontally aligned and evenly spaced around the circle.

Analysis : 
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a unique reference number and date for verification or record-keeping purposes. <!-- figure, from page 0 (l=0.448,t=0.025,r=0.548,b=0.094), with ID 6636eef6-7a1e-469a-91c5-42d0088bd5fe -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- marginalia, from page 0 (l=0.645,t=0.032,r=0.957,b=0.067), with ID e0a4f772-7ba1-4355-a4fa-8887fa463216 -->

<table><tr><td>04/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (VAT Backdate)</td><td>£18434.39</td><td>£49092.41</td></tr><tr><td>07/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-48-45718)</td><td>£2700.00</td><td>£51792.41</td></tr><tr><td>12/03/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£108.93</td></tr><tr><td>12/03/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£51635.48</td></tr><tr><td>14/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-49-45725)</td><td>£2700.00</td><td>£54335.48</td></tr><tr><td>18/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£110.59</td><td>£54224.89</td></tr><tr><td>21/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-50-45732)</td><td>£2700.00</td><td>£56924.89</td></tr><tr><td>24/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£87.77</td><td>£56837.12</td></tr><tr><td>25/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£35.00</td><td>£56802.12</td></tr><tr><td>25/03/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£240.00</td><td>£56562.12</td></tr><tr><td>26/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£55.61</td><td>£56506.51</td></tr><tr><td>28/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-51-45739)</td><td>£2700.00</td><td>£59206.51</td></tr></table> <!-- table, from page 0 (l=0.042,t=0.107,r=0.956,b=0.286), with ID f0cd9919-ca08-4904-872d-dc3b9676fe7f -->

We charge interest each day you are overdrawn. We calculate interest on your end of day account balance. For further information about our interest rates, refer to www.starlingbank.com/legal
Date range applicable: 10/10/2024 - 31/03/2025
<table><thead><tr><th>Interest rate paid on Account Balance</th><th>%AER Variable</th><th>%Gross Variable</th><th>Interest rate charged on Account Balance</th><th>%EAR Variable</th></tr></thead><tbody><tr><td>£0.00 - unlimited</td><td>0.00%</td><td>0.00%</td><td>Less than £0</td><td>0.00%</td></tr></tbody></table> <!-- table, from page 0 (l=0.043,t=0.292,r=0.955,b=0.369), with ID ca3ce5e9-550f-48c9-82da-414445e76217 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.939), with ID 443ac7b7-30ce-4b50-bd5f-4d01c70435ac -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- marginalia, from page 0 (l=0.045,t=0.947,r=0.935,b=0.988), with ID 2e7c9af8-6da5-43e7-910d-38013fa74a3d -->

3 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID 1a7483c8-5dca-442d-9b56-b1c577da3e15 -->
-----------------------------I-------------------------------------------------ICK
ICK --- Using Landing.ai text-based extraction with OpenAI processing
ICK 2 ------------------------------------------------------------------------------
Extracted table content: <table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table>
-----------------------------I-------------------------------------------------ICK 2
2:41:40 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:42 PM [express] GET /api/documents/127/status 304 in 127ms :: {"id":127,"userId":3,"filename":"…
2:41:44 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:41:47 PM [express] GET /api/documents/127/status 304 in 121ms :: {"id":127,"userId":3,"filename":"…
OpenAI raw response: {
  "transactions": [
    {
      "date": "2024-10-11",
      "description": "CARMICHAEL UK",
      "amount": 2066.68,
      "category": "Income",
      "balance": 22024.50
    },
    {
      "date": "2024-10-14",
      "description": "EE",
      "amount": -227.10,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-10-14",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 21777.40
    },
    {
      "date": "2024-10-17",
      "description": "Tahwa Palusi Bowden",
      "amount": -1000.00,
      "category": "Investments",
      "balance": 20777.40
    },
    {
      "date": "2024-10-18",
      "description": "CARMICHAEL UK",
      "amount": 1520.01,
      "category": "Income",
      "balance": 22297.41
    },
    {
      "date": "2024-10-21",
      "description": "Tahwa Palusi Bowden",
      "amount": -300.00,
      "category": "Investments",
      "balance": 21997.41
    },
    {
      "date": "2024-10-25",
      "description": "Tahwa Palusi Bowden",
      "amount": -400.00,
      "category": "Investments",
      "balance": 21597.41
    },
    {
      "date": "2024-11-05",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-11-05",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": 19502.41
    },
    {
      "date": "2024-11-06",
      "description": "Trainline",
      "amount": -29.92,
      "category": "Transportation",
      "balance": 19472.49
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -2000.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -500.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Trainline",
      "amount": -41.49,
      "category": "Transportation",
      "balance": 16931.00
    },
    {
      "date": "2024-11-08",
      "description": "Trainline",
      "amount": -76.60,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-08",
      "description": "Currys",
      "amount": -147.98,
      "category": "Shopping",
      "balance": 16706.42
    },
    {
      "date": "2024-11-09",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 16606.42
    },
    {
      "date": "2024-11-12",
      "description": "EE",
      "amount": -148.57,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Wifi",
      "amount": -5.00,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 16432.85
    },
    {
      "date": "2024-11-13",
      "description": "Trainline",
      "amount": -59.35,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-13",
      "description": "Tahwa Palusi Bowden",
      "amount": -306.00,
      "category": "Investments",
      "balance": 16067.50
    },
    {
      "date": "2024-11-15",
      "description": "Tahwa Palusi Bowden",
      "amount": -260.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -26.47,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -20.08,
      "category": "Transportation",
      "balance": 15760.95
    },
    {
      "date": "2024-11-16",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 15660.95
    },
    {
      "date": "2024-11-22",
      "description": "CARMICHAEL UK",
      "amount": 3040.00,
      "category": "Income",
      "balance": 18700.95
    },
    {
      "date": "2024-11-27",
      "description": "Trainline",
      "amount": -45.45,
      "category": "Transportation",
      "balance": 18655.50
    },
    {
      "date": "2024-11-28",
      "description": "Trainline",
      "amount": -54.78,
      "category": "Transportation",
      "balance": 18600.72
    },
    {
      "date": "2024-11-29",
      "description": "CARMICHAEL UK",
      "amount": 2250.00,
      "category": "Income",
      "balance": 20850.72
    },
    {
      "date": "2024-12-01",
      "description": "Trainline",
      "amount": -41.91,
      "category": "Transportation",
      "balance": 20808.81
    },
    {
      "date": "2024-12-02",
      "description": "1stformations",
      "amount": -1.74,
      "category": "Other",
      "balance": null
    },
    {
      "date": "2024-12-02",
      "description": "Trainline",
      "amount": -39.07,
      "category": "Transportation",
      "balance": 20768.00
    },
    {
      "date": "2024-12-03",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-12-03",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": 18673.00
    }
  ],
  "summary": {
    "totalIncome": 8876.69,
    "totalExpenses": 10189.10,
    "netChange": -1312.41
  }
}
Landing.ai + OpenAI extraction completed: 34 transactions found
Landing.ai OCR extraction complete for page 2 with 34 transactions extracted
Summary: Income: 8876.69, Expenses: 10189.1, Net: -1312.41
Extracted 34 transactions from page 2
Processing page 3 with OCR mode (text content not needed)
Processing page 3 of 3
Extraction method evaluation: 'ai_ocr' === 'ai_ocr' is true
Extraction method type: string
String comparison: 'ai_ocr' === 'ai_ocr' is true
Using AI OCR vision-based extraction for page 3 - TAKING OCR BRANCH
Processing vision-based analysis on file: uploads/pdfs/user_3/1749393590088_StarlingStatement_10-10-2024_31-03-2025.pdf, page: 3
Using Landing.ai vision API for OCR extraction from StarlingStatement_10-10-2024_31-03-2025.pdf page 3
Using full PDF for Landing.ai OCR analysis
Starting OCR extraction with Landing.ai for PDF page 3
Vision data size: 214416 characters
Using Landing.ai for OCR vision analysis
Using Landing.ai Agentic Document Extraction for financial data extraction
2:41:49 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:41:51 PM [express] GET /api/documents/127/status 304 in 121ms :: {"id":127,"userId":3,"filename":"…
2:41:53 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:41:56 PM [express] GET /api/documents/127/status 304 in 122ms :: {"id":127,"userId":3,"filename":"…
2:41:58 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:42:00 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:02 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:05 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:07 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:09 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:12 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:14 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:42:16 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
^[[1;2B^[[1;2B2:42:18 PM [express] GET /api/documents/127/status 304 in 116ms :: {"id":127,"userId":3,"filename":"…
2:42:21 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:23 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:25 PM [express] GET /api/documents/127/status 304 in 115ms :: {"id":127,"userId":3,"filename":"…
2:42:27 PM [express] GET /api/documents/127/status 304 in 116ms :: {"id":127,"userId":3,"filename":"…
2:42:30 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:42:32 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:42:34 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
Landing.ai API response received
Landing.ai API response structure: [ 'data', 'errors', 'extraction_error' ]
Parsed data structure: [ 'markdown', 'chunks', 'extracted_schema', 'extraction_metadata' ]
Has markdown: true
Has chunks: true Count: 27
Landing.ai extracted markdown content length: 24616
Using OpenAI to analyze Landing.ai extracted text
ICK ------------------------------------------------------------------------------
logo: Starling Bank

Visible Elements : 
  • Circular purple icon with a stylized white "S" shape inside.
  • To the right, the text "Starling Bank" in dark blue, with "Starling" above "Bank".
  • Sans-serif font, all text left-aligned.
  • No tagline or additional text present.

Dimensions & Placement : 
  • Icon is approximately the same height as the two lines of text.
  • Icon is placed to the left of the text, with moderate spacing.

Analysis : 
  • The logo uses a simple, modern design with a distinctive icon and clear, bold text, likely aiming for a contemporary and trustworthy brand image. <!-- figure, from page 0 (l=0.041,t=0.027,r=0.245,b=0.080), with ID 39140442-e639-4f3a-83a5-30b73103599f -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a date and reference number.

stamp:  
Shape & Border :  
  • Circular stamp with dotted border.  

Text & Graphic Elements :  
  • Central logo: stylised "S" in a dark circle.  
  • Main text: "Starling Bank" in bold, centered below the logo.  
  • Outer ring text (clockwise):  
    – "TRUE COPY"  
    – "03-05-2023" (date)  
    – "TRUE COPY"  
    – "8345493503" (reference number)  

Ink Colour :  
  • All elements in dark blue.  

Orientation & Placement :  
  • Text and numbers evenly spaced around the circle.  
  • Logo and bank name centered within the stamp.  

Analysis :  
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a specific date and reference number for verification. <!-- figure, from page 0 (l=0.447,t=0.026,r=0.550,b=0.095), with ID 21e39bfc-d54e-4c52-b335-d1a634ce1d81 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.644,t=0.032,r=0.957,b=0.066), with ID d40c4946-4932-4940-92e0-69cd20aa3db4 -->

Prestige Civils Limited  
71-75 Shelton Street  
Covent Garden  
London  
WC2H 9JQ <!-- text, from page 0 (l=0.045,t=0.109,r=0.271,b=0.188), with ID b915653c-a733-4116-8ea9-1e9e17864440 -->

Summary: 10/10/2024 - 31/03/2025

Opening Balance: £19957.82
Payments In: £63086.08
Payments Out: £23837.39
Closing Balance: £59206.51 <!-- text, from page 0 (l=0.516,t=0.106,r=0.945,b=0.249), with ID f50ae3e6-831e-4d0b-bb2c-1e76834e1a74 -->

Account Name: Prestige Civils Limited
IBAN: GB17SRLG60837152721928
BIC: SRLGGB2L
Sort code: 60-83-71
Account Number: 52721928 <!-- text, from page 0 (l=0.043,t=0.203,r=0.483,b=0.279), with ID 31a1fcbe-b7a8-42ef-af74-bf8685d5f632 -->

Summary : This is a logo and certification mark indicating that deposits are protected by the Financial Services Compensation Scheme (FSCS).

logo: FSCS (Financial Services Compensation Scheme) protection mark
  Text & Elements :
    • Stylised "fscs" in lowercase, with a curved underline and partial oval encircling the letters.
    • The word "Protected" appears below the logo in smaller font.
    • To the right, the text reads: "Your deposit is eligible for protection by the Financial Services Compensation Scheme."
  Placement & Dimensions :
    • Logo is positioned on the left, with certification text to the right in a single horizontal line.
    • Font is sans-serif, with the logo in a slightly larger and stylised typeface.
  Colour & Style :
    • Logo and text are in dark purple or black on a white background.
    • Minimalist, official appearance.
  Analysis :
    • The logo certifies that the associated financial product is covered by the FSCS, reassuring customers about deposit protection. <!-- figure, from page 0 (l=0.516,t=0.252,r=0.879,b=0.297), with ID b5e899da-07d5-4ea2-9b78-407d5e04922d -->

10/10/2024 - 31/03/2025 Statement <!-- text, from page 0 (l=0.046,t=0.318,r=0.451,b=0.342), with ID 80118bcd-23ca-497e-8663-daa121739354 -->

<table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table> <!-- table, from page 0 (l=0.042,t=0.352,r=0.957,b=0.898), with ID c7476d98-862e-45ee-977b-eb5d411830a7 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.938), with ID 9da70ddd-dc23-4880-b9dd-06f3fe2367a8 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.045,t=0.947,r=0.938,b=0.988), with ID 5d801839-a992-4b9c-95a6-80034269f1dc -->

1 <!-- marginalia, from page 0 (l=0.931,t=0.978,r=0.943,b=0.987), with ID 0f80cdf8-a484-4cc4-ba33-9255db7e7ba7 -->

logo: Starling Bank

• The image displays the logo for "Starling Bank".
• The logo consists of a solid purple circle containing a stylized white "S" shape.
• To the right of the circle, the words "Starling Bank" are written in a bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" below it.
• The design is simple, modern, and uses a limited colour palette of purple, white, and dark blue.
• The logo is horizontally oriented, with the icon on the left and the text on the right.

Analysis :
• The use of a clean, geometric icon and modern typography suggests a contemporary, digital-first brand identity.
• The purple colour may be intended to convey creativity, trust, or innovation. <!-- figure, from page 0 (l=0.042,t=0.028,r=0.243,b=0.079), with ID 8dd8ff58-75a9-413e-b80d-8fa272474741 -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a date and reference number.

stamp:  
Shape & Border : 
  • Circular stamp with a dotted border.
  • Text "TRUE COPY" repeated twice along the upper and lower arcs of the border.

Text & Graphic Elements : 
  • Central logo: stylized "S" in a dark blue circle.
  • "Starling Bank" written in bold, dark blue, centered below the logo.
  • Date: "03-05-2023" on the right side of the border.
  • Reference number: "B354693503" on the left side of the border.

Ink Colour & Orientation : 
  • All elements in dark blue ink.
  • Upright orientation; text and logo are horizontally aligned.

Dimensions & Placement Cues : 
  • Proportions suggest a small, standard stamp size (exact dimensions not specified).
  • Logo and text are centered within the circular border.

Analysis : 
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a specific date and reference number for traceability. The use of a circular design and consistent dark blue branding reinforces authenticity and corporate identity. <!-- figure, from page 0 (l=0.449,t=0.026,r=0.548,b=0.093), with ID 96f09ccc-80ea-4367-a3bc-ecc366c2eef4 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- text, from page 0 (l=0.645,t=0.032,r=0.957,b=0.066), with ID 14432627-b742-43c2-9496-eb9dace419df -->

<table><tbody><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-35-45627)</td><td>£2250.00</td></tr><tr><td>06/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£20823.00</td></tr><tr><td>12/12/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£122.80</td></tr><tr><td>12/12/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£20652.20</td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-36-45634)</td><td>£2250.00</td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td></tr><tr><td>13/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22702.20</td></tr><tr><td>14/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22602.20</td></tr><tr><td>15/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td><td>£22502.20</td></tr><tr><td>16/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£22302.20</td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-37-45641)</td><td>£2250.00</td></tr><tr><td>20/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£24052.20</td></tr><tr><td>21/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23852.20</td></tr><tr><td>22/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23652.20</td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td></tr><tr><td>24/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23252.20</td></tr><tr><td>25/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£22952.20</td></tr><tr><td>26/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td><td>£22552.20</td></tr><tr><td>30/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£500.00</td><td>£22052.20</td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (DEC 24 - Salary)</td><td>£1095.00</td></tr><tr><td>06/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (DEC 24 - Salary)</td><td>£1047.50</td><td>£19909.70</td></tr><tr><td>08/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£86.55</td><td>£19823.15</td></tr><tr><td>10/01/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£56.52</td></tr><tr><td>10/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-40-45641)</td><td>£2250.00</td><td>£22016.63</td></tr><tr><td>13/01/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£146.61</td><td>£21870.02</td></tr><tr><td>14/01/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£21822.02</td></tr><tr><td>17/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-41-45669)</td><td>£2250.00</td><td>£24072.02</td></tr><tr><td>18/01/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£23872.02</td></tr><tr><td>24/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-42-45676)</td><td>£2250.00</td><td>£26122.02</td></tr><tr><td>31/01/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-43-45683)</td><td>£2025.00</td><td>£28147.02</td></tr><tr><td>02/02/2025</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td>£1.74</td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (JAN 25 - Salary)</td><td>£1047.50</td></tr><tr><td>02/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (JAN 25 - Salary)</td><td>£1047.50</td><td>£26050.28</td></tr><tr><td>03/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£26.98</td></tr><tr><td>03/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£345.00</td><td>£25678.30</td></tr><tr><td>05/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£52.25</td><td>£25626.05</td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-44-45690)</td><td>£2250.00</td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£400.00</td></tr><tr><td>07/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£200.00</td><td>£27276.05</td></tr><tr><td>08/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£26976.05</td></tr><tr><td>12/02/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£108.93</td></tr><tr><td>12/02/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£26819.12</td></tr><tr><td>14/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-45-45697)</td><td>£2250.00</td><td>£29069.12</td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td></tr><tr><td>15/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£80.00</td><td>£28889.12</td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-46-45704)</td><td>£2250.00</td></tr><tr><td>21/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30839.12</td></tr><tr><td>22/02/2025</td><td>CHIP & PIN</td><td>Currys</td><td>£122.00</td></tr><tr><td>24/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£70.00</td><td>£30647.12</td></tr><tr><td>25/02/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£194.10</td><td>£30453.02</td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£100.00</td></tr><tr><td>26/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£300.00</td><td>£30053.02</td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-47-45711)</td><td>£2700.00</td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (FEB 25 - Salary)</td><td>£1047.50</td></tr><tr><td>28/02/2025</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (FEB 25 - Salary)</td><td>£1047.50</td><td>£30658.02</td></tr></tbody></table> <!-- table, from page 0 (l=0.041,t=0.107,r=0.959,b=0.898), with ID 9f671efd-a8ea-4289-895f-5b48788baf45 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.043,t=0.906,r=0.946,b=0.938), with ID 6b056775-0d44-4d24-9361-3fe433995112 -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- text, from page 0 (l=0.046,t=0.947,r=0.927,b=0.987), with ID abd51441-990e-4e77-8270-1ddc6cefd739 -->

2 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID 2bad4e6b-a91a-45e6-a61d-4bf8aca46773 -->

logo: Starling Bank

• The image displays the logo for "Starling Bank".
• The logo consists of a solid purple circle containing a stylized white "S" shape.
• To the right of the circle, the words "Starling Bank" are written in a bold, dark blue sans-serif font, with "Starling" on the top line and "Bank" below it.
• The design is simple, modern, and uses a limited colour palette of purple, white, and dark blue.
• There are no taglines, additional symbols, or other text present.

Analysis :
• The logo uses a clean, minimalist design with a distinctive "S" mark, likely intended to convey modernity and trustworthiness in the banking sector. <!-- figure, from page 0 (l=0.041,t=0.028,r=0.244,b=0.079), with ID bacff10a-f994-4979-8d3f-b320f5723a8f -->

Summary : This is a circular stamp from Starling Bank, indicating a "True Copy" certification with a specific date and reference number.

stamp:  
Shape & Border :  
  • Circular stamp with a dotted border.  

Ink Colour :  
  • Dark blue ink.  

Text & Graphic Elements :  
  • Central logo: stylised "S" in a dark blue circle.  
  • "Starling Bank" in bold, dark blue text, centre-aligned.  
  • Outer ring text (clockwise from top):  
    – "TRUE COPY" (top and bottom, separated by dots).  
    – "02-05-2025" (right side, likely the date).  
    – "3356493503" (left side, likely a reference or serial number).  

Orientation :  
  • Text is evenly spaced around the circumference, upright relative to the logo.  

Dimensions & Placement :  
  • Proportions suggest a standard digital or printed stamp, suitable for document certification.  

Analysis :  
  • The stamp certifies a document as a "True Copy" from Starling Bank, with a clear date and unique reference number for verification. <!-- figure, from page 0 (l=0.448,t=0.025,r=0.548,b=0.094), with ID 5b7bd926-4920-41aa-92fe-2004838356b7 -->

24hr Customer Service: 0207 930 4450  
www.starlingbank.com <!-- marginalia, from page 0 (l=0.645,t=0.032,r=0.957,b=0.067), with ID 88bda9b1-161a-410f-aedf-0ecbcc23accc -->

<table><tr><td>04/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (VAT Backdate)</td><td>£18434.39</td><td>£49092.41</td></tr><tr><td>07/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-48-45718)</td><td>£2700.00</td><td>£51792.41</td></tr><tr><td>12/03/2025</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td>£108.93</td><td></td></tr><tr><td>12/03/2025</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td>£48.00</td><td>£51635.48</td></tr><tr><td>14/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-49-45725)</td><td>£2700.00</td><td>£54335.48</td></tr><tr><td>18/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£110.59</td><td>£54224.89</td></tr><tr><td>21/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-50-45732)</td><td>£2700.00</td><td>£56924.89</td></tr><tr><td>24/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£87.77</td><td>£56837.12</td></tr><tr><td>25/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£35.00</td><td></td></tr><tr><td>25/03/2025</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td>£240.00</td><td>£56562.12</td></tr><tr><td>26/03/2025</td><td>ONLINE PAYMENT</td><td>Trainline</td><td>£55.61</td><td>£56506.51</td></tr><tr><td>28/03/2025</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-51-45739)</td><td>£2700.00</td><td>£59206.51</td></tr></table> <!-- table, from page 0 (l=0.042,t=0.107,r=0.956,b=0.286), with ID 792634f3-2671-4bb2-afb7-bf264e5b505e -->

We charge interest each day you are overdrawn. We calculate interest on your end of day account balance. For further information about our interest rates, refer to www.starlingbank.com/legal
Date range applicable: 10/10/2024 - 31/03/2025
<table><thead><tr><th>Interest rate paid on Account Balance</th><th>%AER Variable</th><th>%Gross Variable</th><th>Interest rate charged on Account Balance</th><th>%EAR Variable</th></tr></thead><tbody><tr><td>£0.00 - unlimited</td><td>0.00%</td><td>0.00%</td><td>Less than £0</td><td>0.00%</td></tr></tbody></table> <!-- table, from page 0 (l=0.043,t=0.292,r=0.955,b=0.369), with ID 69a9a92d-d758-4bb7-abf5-9f1c62972783 -->

Starling Bank is registered in England and Wales as Starling Bank Limited (No. 09092149), 5th Floor, London Fruit and Wool Exchange, 1 Duval Square, London, E1 6PW. We are authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the Prudential Regulation Authority under registration number 730166. <!-- text, from page 0 (l=0.042,t=0.905,r=0.947,b=0.939), with ID 84152604-3b88-4e33-b082-f848c183c90a -->

Our terms and conditions can be accessed via the Starling app or by our website www.starlingbank.com/legal
Starling Bank Limited is a member of the Financial Services Compensation Scheme and the Financial Ombudsman Service. For further information about the compensation provided by the FSCS, refer to the FSCS website at www.fscs.org.uk. Further details can also be found on the FSCS Information Sheet and Exclusion List which are available in the app and on our website. <!-- marginalia, from page 0 (l=0.045,t=0.947,r=0.935,b=0.988), with ID 886ed9e8-e4a3-4188-ab91-64d412878636 -->

3 <!-- marginalia, from page 0 (l=0.930,t=0.978,r=0.944,b=0.988), with ID c9fa9bc2-c0c7-4baf-9774-c8adcca01a4a -->
-----------------------------I-------------------------------------------------ICK
ICK --- Using Landing.ai text-based extraction with OpenAI processing
ICK 2 ------------------------------------------------------------------------------
Extracted table content: <table><thead><tr><th>DATE</th><th>TYPE</th><th>TRANSACTION</th><th>IN</th><th>OUT</th><th>END OF DAY ACCOUNT BALANCE</th></tr></thead><tbody><tr><td></td><td>OPENING BALANCE</td><td></td><td></td><td></td><td>£19957.82</td></tr><tr><td>11/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-27-45571)</td><td>£2066.68</td><td></td><td>£22024.50</td></tr><tr><td>14/10/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£227.10</td><td></td></tr><tr><td>14/10/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£21777.40</td></tr><tr><td>17/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£1000.00</td><td>£20777.40</td></tr><tr><td>18/10/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-28-45578)</td><td>£1520.01</td><td></td><td>£22297.41</td></tr><tr><td>21/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£300.00</td><td>£21997.41</td></tr><tr><td>25/10/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£400.00</td><td>£21597.41</td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>05/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (OCT 24 - Salary)</td><td></td><td>£1047.50</td><td>£19502.41</td></tr><tr><td>06/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£29.92</td><td>£19472.49</td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£2000.00</td><td></td></tr><tr><td>07/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£500.00</td><td></td></tr><tr><td>07/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.49</td><td>£16931.00</td></tr><tr><td>08/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£76.60</td><td></td></tr><tr><td>08/11/2024</td><td>CHIP & PIN</td><td>Currys</td><td></td><td>£147.98</td><td>£16706.42</td></tr><tr><td>09/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£16606.42</td></tr><tr><td>12/11/2024</td><td>DIRECT DEBIT</td><td>EE (T15228979)</td><td></td><td>£148.57</td><td></td></tr><tr><td>12/11/2024</td><td>ONLINE PAYMENT</td><td>Wifi</td><td></td><td>£5.00</td><td></td></tr><tr><td>12/11/2024</td><td>CARD SUBSCRIPTION</td><td>Sky Tv</td><td></td><td>£20.00</td><td>£16432.85</td></tr><tr><td>13/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£59.35</td><td></td></tr><tr><td>13/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£306.00</td><td>£16067.50</td></tr><tr><td>15/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£260.00</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£26.47</td><td></td></tr><tr><td>15/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£20.08</td><td>£15760.95</td></tr><tr><td>16/11/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (P.C.L. Dividend)</td><td></td><td>£100.00</td><td>£15660.95</td></tr><tr><td>22/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-33-45613)</td><td>£3040.00</td><td></td><td>£18700.95</td></tr><tr><td>27/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£45.45</td><td>£18655.50</td></tr><tr><td>28/11/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£54.78</td><td>£18600.72</td></tr><tr><td>29/11/2024</td><td>FASTER PAYMENT</td><td>CARMICHAEL UK (CUK-34-45620)</td><td>£2250.00</td><td></td><td>£20850.72</td></tr><tr><td>01/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£41.91</td><td>£20808.81</td></tr><tr><td>02/12/2024</td><td>CARD SUBSCRIPTION</td><td>1stformations</td><td></td><td>£1.74</td><td></td></tr><tr><td>02/12/2024</td><td>ONLINE PAYMENT</td><td>Trainline</td><td></td><td>£39.07</td><td>£20768.00</td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Tahwa Palusi Bowden (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td></td></tr><tr><td>03/12/2024</td><td>FASTER PAYMENT</td><td>Cameron Slack-Smith (NOV 24 - Salary)</td><td></td><td>£1047.50</td><td>£18673.00</td></tr></tbody></table>
-----------------------------I-------------------------------------------------ICK 2
2:42:36 PM [express] GET /api/documents/127/status 304 in 117ms :: {"id":127,"userId":3,"filename":"…
2:42:39 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:41 PM [express] GET /api/documents/127/status 304 in 119ms :: {"id":127,"userId":3,"filename":"…
2:42:43 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:46 PM [express] GET /api/documents/127/status 304 in 124ms :: {"id":127,"userId":3,"filename":"…
OpenAI raw response: {
  "transactions": [
    {
      "date": "2024-10-11",
      "description": "CARMICHAEL UK",
      "amount": 2066.68,
      "category": "Income",
      "balance": 22024.50
    },
    {
      "date": "2024-10-14",
      "description": "EE",
      "amount": -227.10,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-10-14",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 21777.40
    },
    {
      "date": "2024-10-17",
      "description": "Tahwa Palusi Bowden",
      "amount": -1000.00,
      "category": "Investments",
      "balance": 20777.40
    },
    {
      "date": "2024-10-18",
      "description": "CARMICHAEL UK",
      "amount": 1520.01,
      "category": "Income",
      "balance": 22297.41
    },
    {
      "date": "2024-10-21",
      "description": "Tahwa Palusi Bowden",
      "amount": -300.00,
      "category": "Investments",
      "balance": 21997.41
    },
    {
      "date": "2024-10-25",
      "description": "Tahwa Palusi Bowden",
      "amount": -400.00,
      "category": "Investments",
      "balance": 21597.41
    },
    {
      "date": "2024-11-05",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-11-05",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": 19502.41
    },
    {
      "date": "2024-11-06",
      "description": "Trainline",
      "amount": -29.92,
      "category": "Transportation",
      "balance": 19472.49
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -2000.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Tahwa Palusi Bowden",
      "amount": -500.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-07",
      "description": "Trainline",
      "amount": -41.49,
      "category": "Transportation",
      "balance": 16931.00
    },
    {
      "date": "2024-11-08",
      "description": "Trainline",
      "amount": -76.60,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-08",
      "description": "Currys",
      "amount": -147.98,
      "category": "Shopping",
      "balance": 16706.42
    },
    {
      "date": "2024-11-09",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 16606.42
    },
    {
      "date": "2024-11-12",
      "description": "EE",
      "amount": -148.57,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Wifi",
      "amount": -5.00,
      "category": "Utilities",
      "balance": null
    },
    {
      "date": "2024-11-12",
      "description": "Sky Tv",
      "amount": -20.00,
      "category": "Entertainment",
      "balance": 16432.85
    },
    {
      "date": "2024-11-13",
      "description": "Trainline",
      "amount": -59.35,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-13",
      "description": "Tahwa Palusi Bowden",
      "amount": -306.00,
      "category": "Investments",
      "balance": 16067.50
    },
    {
      "date": "2024-11-15",
      "description": "Tahwa Palusi Bowden",
      "amount": -260.00,
      "category": "Investments",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -26.47,
      "category": "Transportation",
      "balance": null
    },
    {
      "date": "2024-11-15",
      "description": "Trainline",
      "amount": -20.08,
      "category": "Transportation",
      "balance": 15760.95
    },
    {
      "date": "2024-11-16",
      "description": "Tahwa Palusi Bowden",
      "amount": -100.00,
      "category": "Investments",
      "balance": 15660.95
    },
    {
      "date": "2024-11-22",
      "description": "CARMICHAEL UK",
      "amount": 3040.00,
      "category": "Income",
      "balance": 18700.95
    },
    {
      "date": "2024-11-27",
      "description": "Trainline",
      "amount": -45.45,
      "category": "Transportation",
      "balance": 18655.50
    },
    {
      "date": "2024-11-28",
      "description": "Trainline",
      "amount": -54.78,
      "category": "Transportation",
      "balance": 18600.72
    },
    {
      "date": "2024-11-29",
      "description": "CARMICHAEL UK",
      "amount": 2250.00,
      "category": "Income",
      "balance": 20850.72
    },
    {
      "date": "2024-12-01",
      "description": "Trainline",
      "amount": -41.91,
      "category": "Transportation",
      "balance": 20808.81
    },
    {
      "date": "2024-12-02",
      "description": "1stformations",
      "amount": -1.74,
      "category": "Other",
      "balance": null
    },
    {
      "date": "2024-12-02",
      "description": "Trainline",
      "amount": -39.07,
      "category": "Transportation",
      "balance": 20768.00
    },
    {
      "date": "2024-12-03",
      "description": "Tahwa Palusi Bowden",
      "amount": -1047.50,
      "category": "Income",
      "balance": null
    },
    {
      "date": "2024-12-03",
      "description": "Cameron Slack-Smith",
      "amount": -1047.50,
      "category": "Income",
      "balance": 18673.00
    }
  ],
  "summary": {
    "totalIncome": 8876.69,
    "totalExpenses": 10877.60,
    "netChange": -2000.91
  }
}
Landing.ai + OpenAI extraction completed: 34 transactions found
Landing.ai OCR extraction complete for page 3 with 34 transactions extracted
Summary: Income: 8876.69, Expenses: 10877.6, Net: -2000.91
Extracted 34 transactions from page 3
Filtered 0 invalid transactions
Successfully processed document #127 with 102 total transactions
2:42:48 PM [express] GET /api/documents/127/status 200 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:48 PM [express] GET /api/documents/127/status 304 in 118ms :: {"id":127,"userId":3,"filename":"…
2:42:49 PM [express] GET /api/documents/127/summary 200 in 118ms :: {"id":88,"documentId":127,"total…
2:42:49 PM [express] GET /api/documents/127/transactions 200 in 500ms :: [{"id":14757,"date":"2024-1…
2:42:49 PM [express] GET /api/categories 304 in 118ms :: [{"id":12,"name":"Education","backgroundCol…
