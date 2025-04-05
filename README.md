
# 🍔 **RAHMAN FAST FOOD - Shell Script POS System**  
*Bash-Powered Order Management | 3rd Year OS Lab Project*  

---

## 🚀 **Core Features**  
✅ **Interactive Order System**  
- Dynamic menu with multi-size pricing (6/8/10/12-inch options)  
- Real-time inventory tracking (50+ items)  
- Auto-discounts (10% on orders >1000৳)  
- Gift wrapping (+50৳) & recipe customization (spice/salt/cheese)  

✅ **Automated Workflow**  
```bash
- Order logging to restaurant.txt
- PDF receipt generation via pandoc
- Table reservations & order cancellation
- Simulated delivery tracking
```

✅ **Admin Control Panel**  
`Secure Login (admin123)` | Sales Analytics | Employee Management | Feedback Analysis  

---

## ⚙️ **Technical Highlights**  
**OOP Implementation**  
```bash
case $item_no in
  1) item_name="Chicken Pot Pie"; price=150 ;;
  ...
  10) item_name="Bread Sticks"; price=90 ;;
esac
```

**Inventory Management**  
```python
inventory = {1:50, 2:100, ..., 10:90}  # Item-based stock
if stock >= order_qty:
    update_inventory()
else:
    alert("Low stock!")
```

**Dynamic Pricing**  
`Base Price + Size Premium + Customization Charges`  
```bash
total=$((price * qty))
(( total > 1000 )) && total=$((total - (total/10)))  # 10% discount
```

---

## 🛠️ **Tech Stack**  
`Bash 5.1` | `pandoc` | `GNU Coreutils` | `CRON Jobs`  

---

## 🧠 **Smart Features**  
🔹 **Multi-Payment Support**  
`Cash | Card | Mobile Banking`  

🔹 **Customer Engagement**  
- Feedback system → feedback.txt  
- Order history tracking (phone/email lookup)  

🔹 **Error Handling**  
```diff
+ Input validation for all user entries
+ Graceful exit on errors (exit 1)
```

---

## 📊 **Admin Capabilities**  
1️⃣ View all orders  
2️⃣ Analyze sales trends  
3️⃣ Manage employees (add/remove/update)  
4️⃣ Monitor customer feedback  
5️⃣ Generate financial reports  

---

## � **Future Roadmap**  
» SMS/Email notifications  
» Loyalty program integration  
» Graphical UI (Dialog/Whiptail)  
» API integration for delivery tracking  

---

