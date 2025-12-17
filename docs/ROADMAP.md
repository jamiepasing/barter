## Development Roadmap
**Barter** is a web and Cordova-based POS and inventory management application designed for sari-sari stores. It modernizes traditional local retail operations by providing a FIFO-based inventory handling, expiration tracking, profit monitoring, and simple POS transactions in an easy-to-use interface.<br>
<br>
This roadmap outlines Barter's development plan.<br>

### **Phase 1** - Foundation & System Design (1st Month)
> Establish the project's technical base, data structure, and usability principles
<br>
- Set up web application structure and GitHub repository <br>
- Initialize Cordova environment for mobile development <br>
- Configure database (MySQL) and environment variables <br>
- Define overall system architecture (Inventory → FIFO Engine → POS → Reports) <br>
- Design database schema for products, stock batches, categories, and sales transactions <br>
- Define pricing logic (purchase price + user-defined markup = resale price) <br>
- Define the FIFO stock priority regardless of price differences <br>
- Produce low-fidelity wireframes focused on ease of use for users with varying levels of technological proficiency <br>
- Create initial documentation and system flow diagrams <br>

**Deliverable:** Project skeleton with finalized database schema and UI wireframes 

### **Phase 2** - Core Inventory and POS MVP (2nd Month)
> Build the essential inventory and sales functionalities
<br>
- Implement product and category management (Food, Hygiene, Household items, Office products, etc.)<br>
- Implement stock entry with quantity, purchase price, markup, and expiration date <br>
- Implement FIFO-based stock deduction during sales transactions <br>
- Automatically update stock levels when new orders are completed <br>
- Handle multiple stock batches with varying purchase prices <br>
- Implement POS transaction flow (add item, compute total, checkout)<br>
- Implement transaction voiding and correction mechanism <br>
- Resore stock quantities and FIFO order when a transaction is removed or canceled <br>
- Recalculate income and profit values after transaction rollback <br>
- Implementat expiration monitoring and near-expiry alerts <br>

**Deliverable:** Functional POS and inventory system with FIFO logic and expiration tracking

### **Phase 3** - Reporting, UX Refinement, and Deployment (3rd Month)
> Improve usability, provide insights, and prepare the system for real-world use 
<br>
- Implement sales and income reports (daily, weekly, monthly, annual) <br>
- Compute profit estimates based on sales and purchase costs <br>
- Create dashboard summaries (inventory value, income, low-stock alerts)<br>
- Enhance UX with larger fonts, clear icons, and color indicators <br>
- Add basic data export and back up functionality (CSV)<br>
- Test Cordova build on android devices <br>
- Conduct usability testing with users <br>
- Prepare deployment and installation documentation <br>

**Deliverable:** Barter MVP ready for pilot deployment (Web and Android)