# Cahier des Charges for Wallpaper eCommerce Platform

## 1. Project Overview

**Project Name:** Wallpaper Haven  

**Objective:** Design and implement a robust eCommerce platform that enables users to browse, preview, customize, and purchase wallpapers efficiently.  

**Core Features:**  
- Real-time wallpaper preview functionality on different wall types.  
- A user-driven wallpaper customization tool.  
- Seller portal for managing wallpaper listings.  
- Secure and seamless transaction processing.  

---

## 2. Stakeholders

**Client:** University Capstone Project  

**Development Team:** [Your Name or Team]  

**End Users:**  
- **Visitors:** Can explore wallpapers but lack purchasing privileges.  
- **Buyers (Registered Users):** Can purchase wallpapers and design their own custom styles.  
- **Sellers:** Have access to an exclusive dashboard to upload, manage, and market their wallpapers.  
- **Administrator:** Oversees the platform, handling user management, product moderation, and order fulfillment.  

---

## 3. Functional Requirements

### User Features (Front Office)  
**Browsing & Filtering:**  
- Users can filter wallpapers by color, pattern, material, and price.  
- Advanced search with keyword matching.  

**Interactive Wallpaper Preview:** ✅  
- Users can visualize selected wallpapers on predefined room templates.  
- Optional feature for uploading personal room images (Advanced functionality).  

**Wallpaper Customization Module:**  
- Buyers can create personalized wallpaper designs using a dedicated editor.  
- Upload custom images and apply modifications like scaling, effects, or tiling.  

**User Authentication & Profile Management:**  
- Secure account registration and login.  
- User dashboard to track orders and manage saved wallpapers.  

**Shopping Cart & Payment Processing:**  
- Ability to add multiple wallpapers to the cart.  
- Secure checkout options (cash-on-delivery initially, with possible Stripe/PayPal integration in later phases).  

### Seller Features  
**Seller Dashboard:**  
- Interface to upload and manage wallpaper listings.  
- Pricing and stock adjustments.  
- Sales analytics and order management.  

### Admin Features (Back Office)  
**Product & Order Management:**  
- CRUD operations on wallpaper listings.  
- Order tracking and fulfillment.  

**User & Seller Management:**  
- Ability to approve or suspend seller accounts.  
- Review and moderate uploaded wallpapers.  

---

## 4. Technical Specifications

**Frontend Stack:** HTML, Tailwind CSS, Vanilla JavaScript  

**Backend Stack:** PHP with MySQL (using PDO for database interactions and security enhancements)  

**Database Structure:**  
- Tables for users, wallpapers, orders, and transactions.  
- Indexing strategies for optimized query performance.  

**Hosting & Deployment:**  
- Initial testing on local environments.  
- Production deployment considerations (e.g., VPS or cloud hosting options).  

---

## 5. UI/UX Considerations

- Wireframes should illustrate key pages, including:  
  - Homepage  
  - Product detail and preview pages  
  - Wallpaper customization tool  
  - Seller dashboard  
  - Checkout and payment processing  
- A mobile-responsive design strategy should be integrated.  
- Accessibility compliance for a diverse user base.  

---

## 6. Project Timeline & Milestones

| **Phase** | **Task** | **Estimated Completion** |  
|-----------|----------|--------------------------|  
| Phase 1   | Project initiation, research, and tech stack setup | [Date] |  
| Phase 2   | Database design, authentication, and seller onboarding | [Date] |  
| Phase 3   | Wallpaper preview and customization module development | [Date] |  
| Phase 4   | eCommerce functionalities (cart, checkout, transaction handling) | [Date] |  
| Phase 5   | Testing, debugging, security enhancements, and deployment | [Date] |  

---

## 7. Constraints & Risks

- **Time Limitation:** Project completion within a four-month timeframe.  
- **Technical Complexity:** Implementing real-time wallpaper visualization efficiently.  
- **Security Considerations:**  
  - Protection against SQL injection and XSS attacks.  
  - Secure payment processing compliance.  

---

## Next Steps

1. Establish a database schema and document relationships.  
2. Create initial wireframes and UI prototypes.  
3. Set up a GitHub repository and development workflow.  
