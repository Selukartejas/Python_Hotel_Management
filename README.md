**Taj Hotel - Restaurant Management System**

**Introduction:**
Welcome to the documentation for Taj Hotel's Restaurant Management System. This system is designed to streamline the ordering process, manage bills, apply discounts, and generate detailed multi-bills.

---

**Classes:**

1. **TajHotel:**
   - **welcomeGuest(self, obj):**
     - Greets the guest and initiates the menu display using the `getMenu` function of the Menu class.

2. **Menu:**
   - **newOrder(self, total, obj, qty):**
     - Facilitates placing new orders, calculates final bills, applies day-based discounts, and handles additional orders.
   - **getMenu(self, obj):**
     - Presents menu options and manages user order input.

3. **MultiBill:**
   - **generateMultiBill(self, obj):**
     - Outputs a detailed multi-bill, displaying dish names, prices, quantities, and total amounts.

4. **MenuPrint:**
   - **snacks(self):**
     - Displays snack menu options.
   - **veg(self):**
     - Displays vegetarian meal menu options.
   - **nonVeg(self):**
     - Displays non-vegetarian meal menu options.
   - **dessert(self):**
     - Displays dessert menu options.

5. **DishName:**
   - Holds constants for dish names.

6. **Price:**
   - Holds constants for dish prices.

7. **Bill:**
   - **updateBill(self, amt, qty):**
     - Updates the total bill based on the price and quantity of an ordered item.
   - **printBill(self):**
     - Returns the current total bill.

8. **Count:**
   - Tracks the quantity of each ordered item.

9. **ObjectFactory:**
   - Creates instances of all classes required for the restaurant management system.

---

**Usage:**
1. Create an instance of the `ObjectFactory` class.
2. Access different functionalities through the methods provided by respective classes.

Feel free to explore and modify the code to meet specific restaurant needs. For any queries or further assistance, refer to the comments in the code or reach out to the developer.

Thank you for choosing Taj Hotel's Restaurant Management System! We hope you have a delightful dining experience!
