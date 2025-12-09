# ARKA - E-commerce Backend System

## Overview
ARKA is a comprehensive e-commerce backend solution that streamlines online store operations through secure transactions, intelligent inventory management, and automated workflows. Built with modern technologies and microservices architecture, ARKA solves critical challenges in e-commerce operations.

## Problems We Solve

### 1. **Abandoned Cart Recovery**
**Problem:** Customers add products to their cart but leave without completing the purchase, resulting in lost revenue.

**Solution:** Automated cart abandonment detection and personalized email reminders.
- Webhook-triggered workflow when a cart is abandoned
- Sends friendly, personalized emails with cart details
- Includes product names, quantities, and total price
- Encourages customers to complete their purchase

### 2. **Order Status Communication**
**Problem:** Customers are uncertain about their order status, leading to support inquiries and poor experience.

**Solution:** Automated order status notifications via email.
- Real-time updates for three shipping stages:
  - **Confirmed/Preparing:** Order confirmed and being processed
  - **In Transit:** Package is on its way
  - **Delivered:** Order successfully delivered
- Personalized messages for each stage
- Includes order ID and support contact information

### 3. **Inventory Management**
**Problem:** Products running out of stock without warning, causing lost sales and customer dissatisfaction.

**Solution:** Proactive low-stock alerts to administrators.
- Monitors inventory levels in real-time
- Triggers notifications when stock falls below threshold
- Provides supplier contact information automatically
- Enables quick reordering to prevent stockouts

### 4. **Sales Analytics & Reporting**
**Problem:** Lack of insights into sales performance, making it difficult to make data-driven business decisions.

**Solution:** AI-powered weekly sales reports with actionable insights.
- Automated weekly report generation (every 7 days)
- AI analysis of sales data using GPT-4
- Generates comprehensive reports including:
  - Best-selling products
  - Revenue analysis
  - Sales trends and patterns
  - Progress toward targets
  - Cancelled order analysis
- Automatically delivered via email as PDF
- Data stored in Google Sheets for easy access

### 5. **Sales Data Persistence**
**Problem:** Need to track and analyze every order (confirmed and cancelled) for business intelligence.

**Solution:** Automatic order logging to centralized database.
- Captures all order details in real-time
- Handles single and multiple item orders
- Stores: product ID, quantity, unit price, subtotal, date, and status
- Google Sheets integration for easy data access and analysis
- Supports historical sales tracking

---

Built with ❤️ as part of AceleraTI Latam's Java Backend Developer Program
