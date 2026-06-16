# Junaid Jamshed SQE Automation Tests

Automated UI testing suite for the Junaid Jamshed e-commerce website using Selenium WebDriver and NUnit.


## Features: 

. 15 Test Cases covering navigation, search, categories, cart, and checkout

. Automated Browser Testing with ChromeDriver

. Comprehensive Coverage:

   . Homepage loading

   . Cookie consent

   . Search functionality

   . Mobile menu navigation

   . Category browsing

   . Product selection

   . Cart operations (add, update, remove)

   . Checkout flow

. Robust Selectors with fallback mechanisms

. Smooth Execution with JavaScript scroll/click helpers

## Tech Stack:

. .NET 8.0

. NUnit (Test Framework)

. Selenium WebDriver 4.44.0

. Selenium.Support 4.44.0

. ChromeDriver 148.0.7778.16700

. C# (Language)

## Test Cases:

TC_NAV_01 = Homepage loads successfully

TC_COOKIE_02 = Accept cookies and select country

TC_SRC_03 = Search returns relevant results

TC_MENU_04 = Open mobile menu and select Women

TC_CAT_05 = Click on Artisanal category

TC_CAT_06 = Verify the Artisanal page opens with products

TC_PROD_07 = Click first product and navigate to product page

TC_CART_08 = Add product to cart

TC_CART_09 = Return to shop from cart

TC_CART_10 = View cart and verify items

TC_CART_11 = Update quantity in cart

TC_CART_12 = Remove item from cart

TC_CART_13 = Continue shopping from cart

TC_CART_14 = Proceed to checkout

TC_CART_15 = Verify checkout and return to cart

## Prerequisites: 

. .NET SDK 8.0 or higher

. Google Chrome browser

. ChromeDriver (automatically installed via NuGet)

. Visual Studio 2022 / VS Code

## Configuration:

. The tests target the live website: https://www.junaidjamshed.com/

## Helper Methods:

. JsClick() - Scroll to element and click using JavaScript

. SafeClick() - Try-catch wrapper for safer execution

. AcceptCookiesAndSelectCountry() - Handle initial popups

. OpenMobileMenuAndSelectWomen() - Navigate menu structure

. ClickArtisanal() - Drill down to subcategory

. ClickFirstProduct() - Select first product from listing

