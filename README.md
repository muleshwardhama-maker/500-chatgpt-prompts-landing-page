# 500 ChatGPT Prompts for Indian Businesses — Landing Page Starter

This is the first frontend version for the ₹149 ebook offer.

## Files
- `index.html` — responsive landing page with product explanation, 10 ebook categories, sample prompt copy button, FAQs and purchase CTA.
- `ebook-cover.png` — cover image extracted from the uploaded PDF.

## Preview locally
Open `index.html` in a browser. The sample prompt copy button works. The buy button intentionally shows a setup notice because Razorpay is not connected yet.

## Important before launch
This is a frontend starter, not a live payment system. Do not claim payments or email delivery work until the backend is built and tested. The production setup still needs:
1. GitHub repository.
2. Render deployment and backend service.
3. Razorpay order creation and signature/webhook verification on the server.
4. A transactional email provider with verified sender/domain.
5. Paid order storage and retry-safe email delivery.
6. Secure ebook download delivery.
7. Seller contact details, privacy policy, terms and digital-product refund policy.

Never put Razorpay secret keys or email API keys in `index.html` or any public GitHub repository.
