## 🏭 ClothSphere - Garment Manufacturing & E-commerce Management System
ClothSphere is a comprehensive enterprise management system designed for garment manufacturing companies, integrating production, inventory, sales, HR, e-commerce, and employee self-service operations into a unified platform.

## 📋 System Overview
The system serves as a complete solution for managing all aspects of a garment manufacturing business, from raw material inventory and production workflow to online sales, HR operations, and employee self-service portals.

## 👥 User Roles & Dashboards
Your system supports 7 distinct user roles, each with specialized dashboards:

### 1. HR Manager Dashboard (hrDashboard.html)
Complete employee lifecycle management
Manager oversight and department organization
Comprehensive attendance tracking and reporting
Advanced leave management with approval workflows
Automated payroll processing and generation
Workload assignment and employee distribution
Department budgeting and salary management
Performance monitoring and reporting

### 2. Officer Dashboard (officerDashboard.html)
Product catalog management and pricing
Customer inquiry and complaint handling
Buyer communication management
Product listing and description updates

### 3. Factory Manager Dashboard (factoryManagerDashboard.html)
Production task creation and scheduling
Staff assignments and workload balancing
Real-time production monitoring
Performance tracking by department/employee
Production deadline management
Task priority assignment (P0-P3 criticality levels)

### 4. Sales Executive Dashboard (salesDashboard.html)
Dual order creation (local physical & online)
Customer relationship management (CRM)
Order tracking from creation to delivery
Sales reporting and revenue analytics
Customer database management
Discount application and management
Online buyer account oversight

### 5. Inventory Manager Dashboard (inventorydashboard.html)
Fabric & garment stock categorization
Real-time stock monitoring and alerts
Movement trend analysis (IN/OUT)
Rejection tracking and quality control
Low stock automatic alerts
Weekly stock movement visualization
Inventory reporting and forecasting

### 6. Buyer Dashboard (buyerDashboard.html)
Secure shopping cart and checkout
Order history and tracking
Wishlist management
Customer profile management
Contact and inquiry system
Collection browsing by category

### 7. Employee Dashboard (employeeDashboard.html)
Profile management with secure password reset
Attendance tracking with a check-in/check-out system and notes
3-tier leave management system with approval workflow
Task assignment viewing and progress tracking
Paysheet viewing with detailed breakdowns (gross/net salary, deductions)
Internal communication system for inter-department messaging

## 🔑 Core System Components
Authentication & Security
Multi-role based access control (RBAC)
Secure login system (systemUserLogin.html) with first-time password setup
Password strength validation and management
Session handling and timeout protection
Role-specific navigation and permissions

### Internal Communication System (internal-communication.html)
Inter-department messaging with role-based restrictions
Communication rules (e.g., Employees cannot message Factory Manager directly)
Message tracking with read/unread status
Professional communication guides and best practices
Sent messages archive


## 💻 Technical Implementation
Frontend Technologies
HTML5 with semantic, accessible structure
CSS3 with responsive design using Flexbox/Grid
Vanilla JavaScript for dynamic interactions
Chart.js for data visualization and analytics
Font Awesome 6.4 for modern icons
Responsive layouts for all device types
Modal-based UI for forms and details

## Architecture Features
Modular dashboard design with sidebar navigation
Role-based navigation and permissions
Form validation with real-time feedback
Dynamic data loading via JavaScript
Table-based data presentation with filtering
Progress visualization for task/attendance


## Key Functionalities
Dashboard switching with smooth transitions
Form validation with error handling
Data filtering and search capabilities
Export capabilities (reports, payroll)
Media integration (videos, images)
Calendar integration with notes (HR)
Real-time display (Sales)

## 🎯 Business Benefits
For Manufacturing Operations
Streamlined production workflow with clear task assignments
Optimized inventory management with real-time stock visibility
Improved inter-department communication, reducing delays
Data-driven decision making with comprehensive analytics
Quality control through rejection tracking


## 🛠️ Development Status
### Completed Features
✅ Complete 7-role architecture with specialized dashboards
✅ Functional dashboard interfaces for all user types
✅ Comprehensive form systems with validation
✅ Basic data visualization using Chart.js
✅ Responsive design principles across all screens
✅ Modular JavaScript organization by dashboard
✅ Employee self-service portal with full functionality
✅ 3-tier leave management system
✅ Attendance tracking with notes
✅ Detailed paysheet viewer

Ready for Backend Integration
Database schemas implied by frontend forms
API endpoints suggested by JavaScript functions
Data models are clear from the table structures
Workflow processes defined in UI interactions

### Technical Excellence
Clean separation of HTML/CSS/JavaScript
Consistent design language across dashboards
Accessibility considerations in markup
Performance optimization with lazy loading
Security awareness in form design
