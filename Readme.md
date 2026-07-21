# UrbanStyle Clothing

## Project Overview

UrbanStyle Clothing is an e-commerce fashion store website designed to showcase and sell modern clothing, footwear, handbags, and fashion accessories.

The website allows customers to browse products, view product details, and contact the company through a simple and user-friendly interface.

This project was created using HTML, CSS, Git, and GitHub as part of a web development final project.

---

## Project Objectives

The main objectives of UrbanStyle Clothing are:

- Create a professional online fashion store
- Design a clean and attractive user interface
- Display fashion products in an organized catalogue
- Provide detailed product information
- Build a foundation for future e-commerce features

---

# Features

## Customer Pages

### Homepage
- Brand introduction
- Hero section
- Featured collections
- Navigation menu

### About Page
- Company information
- Brand mission
- Company values

### Shop Page
- Product catalogue
- Product cards
- Product prices
- Product descriptions

### Product Pages
- Individual product details
- Product images
- Product information
- Product categories

### Contact Page
- Customer contact form
- Business information
- Communication details

---

# Technologies Used

## Frontend

- HTML5
- CSS3

## Development Tools

- Visual Studio Code
- GitHub Desktop
- GitHub
- Live Server Extension

---

# Project Structure

```text
urbanstyle-clothing

│── index.html
│── README.md
│
├── css
│   └── style.css
│
├── images
│   ├── tshirt.jpg
│   ├── hoodie.jpg
│   ├── shoes.jpg
│   └── handbag.jpg
│
├── pages
│   ├── about.html
│   ├── shop.html
│   └── contact.html
│
├── products
│   ├── tshirt.html
│   ├── hoodie.html
│   ├── shoes.html
│   └── handbag.html
│
│
└── docs
    └── wireframes.md
```

---

# Design System

## Colour Scheme

### Primary Colour

Black (#111111)

Used for:
- Navigation bar
- Buttons
- Footer
- Brand identity


### Secondary Colour

White (#FFFFFF)

Used for:
- Website backgrounds
- Main content areas


### Accent Colour

Light Grey (#F4F4F4)

Used for:
- Hero sections
- Product cards
- Content sections

---

# Typography

The website uses two different fonts:

## Playfair Display

Used for:

- Brand logo
- Main headings
- Section titles


## Poppins

Used for:

- Navigation links
- Paragraph text
- Product descriptions

---

# Website Pages

## Homepage Layout

```text
--------------------------------

Navigation Bar

--------------------------------

Hero Section

Brand Heading
Description
Shop Button

--------------------------------

Featured Products

Product Cards

--------------------------------

Footer

--------------------------------
```

---

## Shop Page Layout

```text
--------------------------------

Navigation Bar

--------------------------------

Shop Heading

--------------------------------

Product Grid

Product | Product | Product

Product | Product | Product

--------------------------------

Footer

--------------------------------
```

---

## Product Page Layout

```text
--------------------------------

Navigation Bar

--------------------------------

Product Image

Product Name

Product Price

Description

Add To Cart Button

--------------------------------

Footer

--------------------------------
```

---

# Database Structure Plan

Future database implementation will contain the following tables:

## Products Table

| Field | Description |
|---|---|
| product_id | Unique product identifier |
| product_name | Name of product |
| category | Product category |
| description | Product details |
| price | Product price |
| image | Product image |
| stock_quantity | Available stock |

---

## Customers Table

| Field | Description |
|---|---|
| customer_id | Unique customer identifier |
| first_name | Customer first name |
| last_name | Customer last name |
| email | Customer email |
| phone | Customer phone number |

---

## Orders Table

| Field | Description |
|---|---|
| order_id | Unique order identifier |
| customer_id | Customer reference |
| order_date | Purchase date |
| total_amount | Total order price |

---

# Installation Instructions

## Clone Repository

```bash
git clone https://github.com/niteshbassai/urbanstyle-clothing.git
```

## Open Project

Open the project folder using Visual Studio Code.

## Run Website

Open:

```text
index.html
```

using the Live Server extension.

---

# Future Improvements

Future updates may include:

- Shopping cart functionality
- Customer accounts
- Online payment system
- Product database integration
- Search functionality
- Admin dashboard
- Order management system

---

# Git Commit History

The project follows regular Git version control practices.

Example commits:

```text
Initial project structure for UrbanStyle Clothing website

Create UrbanStyle homepage layout and styling

Create company about page and brand information section

Create shop page with product catalogue layout

Create individual product pages for fashion catalogue

Create contact page with customer inquiry form

Add project documentation, wireframes, and database planning
```

---

# Author

Nitesh Bassai

---

# License

This project is created for educational purposes.