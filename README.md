# Abra Cart Drawer Banners

A lightweight Shopify snippet for displaying promotional banners in your cart drawer.

## Features

- Easy to implement
- Fully customizable through CSS
- Compatible with any Shopify theme

## Installation

1. Copy the `snippets/abra-cart-drawer-banners.liquid` file into your theme's snippets directory
2. Add the render tag to your cart drawer template

## Usage

Add the following code to your cart drawer template:

```liquid
{% render 'abra-cart-drawer-banners' %}
```

## Styling

The banners use semantic CSS classes for easy customization. You can override the default styles by:

1. Adding your custom CSS to a global stylesheet
2. Ensuring your CSS file is loaded on all pages where the cart drawer appears
