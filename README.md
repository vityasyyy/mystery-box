# Identitas
## Nama, NIM, Kelas, Dosen Pengampu
- Andrian Danar Perdana (23/513040/PA/21917)
- Daffa Indra Wibowo (23/518514/PA/22253)
- Muhammad Argya Vityasy (23/522547/PA/22475)
- Rayhan Firdaus Ardian (23/519095/PA/22279)

WRPL KOM A, Guntur Budi Herwanto, S.Kom., M.Cs.

---

# 🎁 Mystery Box E-Commerce App

A platform where users can purchase randomized mystery boxes containing various items (electronics, fashion, collectibles), complete with secure payments and order tracking.

---

## 🚀 Initiative

**Goal:** Create a gamified shopping experience where users purchase sealed boxes containing random items of specified categories/value ranges.

---

## 🧩 Features

### ✅ MVP Goals
- [ ] User authentication (sign up/login)
- [ ] Mystery box product listings with categories/price tiers
- [ ] Shopping cart system
- [ ] Checkout process with payment gateway integration
- [ ] Order history with revealed box contents
- [ ] Admin panel for box management

### 🧠 Future Improvements
- [ ] Referral system with rewards
- [ ] Limited edition boxes
- [ ] Wishlist feature
- [ ] Mystery box customization (price range, preferred categories)
- [ ] Live unboxing animations

---

## 📦 User Stories

### 🧍 As a User:
- "I want to browse mystery boxes by category/price"
- "I want to see what others received in their boxes"
- "I want to securely pay and instantly see my box contents"
- "I want to track my order history"

### 👔 As an Admin:
- "I need to manage box inventory/odds"
- "I want to view sales analytics"
- "I need to upload box content items"

---

## ✅ Acceptance Criteria (MVP)
- [ ] Users can purchase boxes in 3+ categories (e.g., Tech, Fashion, Sports)
- [ ] Payment integration with Stripe/Midtrans
- [ ] Randomized item distribution algorithm
- [ ] Mobile-responsive design
- [ ] Order confirmation email/SMS
- [ ] Admin dashboard with CRUD operations

---

## 🛠️ Tech Stack

| Frontend        | Backend         | Payments           |
|-----------------|-----------------|--------------------|
| Next.js/React   | Node.js/Express | Stripe API         |
| Tailwind CSS    | Python/Django   | Midtrans (ID)      |
| Zustand/Redux   | PostgreSQL      | PayPal API         |
| Framer Motion   | MongoDB         | Payment gateway SDK|

**Additional:**
- Cloudinary (for product images)
- Redis (for caching)
- Docker (containerization)
- GitHub Actions (CI/CD)

---

## 🔒 Security Considerations
1. PCI Compliance for payments
2. SSL encryption
3. Rate limiting for API endpoints
4. Role-based access control
5. Audit logs for sensitive operations

---

## 🗂️ Agile Project Structure

**Epics:**
1. User Authentication
2. Product Management
3. Cart & Checkout
4. Payment Integration
5. User Dashboard
6. Admin Panel

**Sprints:**
- 2-week sprints with GitHub Project Board
- Daily standups (async via Discord/Slack)
- Weekly demo sessions

---

## 💰 Monetization Strategies (Optional)
1. Percentage cut from each box sale
2. Premium membership for better odds
3. Sponsored boxes from brands
4. In-app currency system

---

## 🚨 Risk Management
1. **Legal Compliance:** Ensure gambling laws compliance in target regions
2. **Inventory Management:** Algorithm for item distribution odds
3. **Fraud Prevention:** Implement anti-bot measures
4. **User Trust:** Clear terms about box odds/content value
