# Extra Product

## Description

This Drupal recipe adds a "Product" content type to your site. It provides a comprehensive set of fields and configurations to manage products effectively.

## Requirements

This recipe requires the following Drupal modules and packages:

- Drupal Core (>=10.4 || ^11)
- Entity Reference Revisions (`drupal/entity_reference_revisions`)
- Font Awesome (`drupal/fontawesome`)
- Image Widget Crop (`drupal/image_widget_crop`)
- Paragraphs (`drupal/paragraphs`)
- Video Embed Field (`drupal/video_embed_field`)
- Extra Paragraphs
- Extra View Modes

The recipe will automatically install the following modules if they are not already enabled:

- `entity_reference_revisions`
- `file`
- `image`
- `image_widget_crop`
- `link`
- `menu_ui`
- `node`
- `options`
- `paragraphs`
- `path`
- `taxonomy`
- `text`
- `user`
- `video_embed_field`

## Installation

1.  Add the recipe to your project's `composer.json` file:
    ```bash
    composer require morethanthemes/extra_product
    ```
2.  Apply the recipe using Drush:
    ```bash
    drush recipe apply extra_product
    ```
    Or, if you are using the recipes from a local path, you can run:
    ```bash
    drush recipe apply path/to/extra_product
    ```

## Configuration

This recipe creates a new content type called "Product" (`mt_product`). The content type is pre-configured with the following fields:

- **Additional Features**: Paragraphs for highlighting extra product features.
- **Availability**: The product's availability status.
- **Body**: The main description of the product.
- **Buy Link**: A link to purchase the product.
- **Categories**: Taxonomy terms for categorizing the product.
- **Content Collapses**: Collapsible content sections.
- **Content Tabs**: Tabbed content sections.
- **Delivery Options**: Information about delivery.
- **Highlight**: A field to highlight the product.
- **Image**: The main product image.
- **Landscape Image**: A landscape-oriented image for the product.
- **Most Popular**: A flag to mark the product as "most popular".
- **Price**: The price of the product.
- **Pricing Table Item**: A field for pricing table integration.
- **Product Code**: The product's code or SKU.
- **Specifications**: Paragraphs for product specifications.
- **Subheader Body**: A secondary body text.
- **Subtitle**: A subtitle for the product.
- **Tags**: Taxonomy terms for tagging the product.
- **Teaser Image**: An image for teaser displays.
- **Video**: An embedded video for the product.

The recipe also configures several view modes for the "Product" content type, including:

- Default
- Metro Tile
- Slide View
- Teaser Compact
- Teaser Tile
- Video Grid Item
- Teaser

This recipe provides a solid foundation for a product-centric Drupal site. You can further customize the content type and its fields to meet your specific needs.
