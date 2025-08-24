# 🍔 Javeats Food Delivery System

A food delivery system built with **Java** and **Spring Boot**.
This project demonstrates core backend concepts such as **order management, restaurant management, user accounts, and delivery tracking**.

---

## 📑 Table Of Contents

* [Overview](#-overview)
* [Features](#-features)
* [Flowchart](#-flowchart)
* [Sequence Diagram](#-sequence-diagram)
* [ERD](#-erd)
* [psuedo code](#-psuedo-code)

---

## 🔎 Overview

Javeats is a simple food delivery platform that simulates the main functionalities of modern food ordering systems.
It is designed as a learning project for backend engineering using Spring Boot.

---

## ✨ Features

* 🍴 **Restaurant Management** – add/remove restaurants & meals
* 🛒 **Order Management** – add to cart, place order, cancel order
* 👤 **User Accounts** – register, login, manage account
* 🚚 **Delivery Tracking** – track orders in real-time (simulation)
* 💳 **Payment Options** – choose payment method (e.g., COD, online)

---

## 📊 Flowchart

![flowchart](/docs/cart-management.png)

---

## 📈 Sequence Diagram

![sequence diagram](/docs/sequence-diagram.png)

---

## 📊 ERD

![ERD](/docs/ERD.png)

---

## 📝 Psuedo Code

```pseudo
START

USER enters website

DISPLAY list of available restaurants

USER selects a restaurant

DISPLAY restaurant menu (list of items)

WHILE user wants to add items:
    USER selects item
    USER specifies quantity
    ADD item to CART

USER opens CART
DISPLAY items in CART

IF USER updates quantity OR removes item:
    UPDATE CART in database

IF USER confirms order:
    SAVE order details to database
    REDUCE stock quantity of ordered products

END
```
