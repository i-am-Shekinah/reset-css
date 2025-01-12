# A More Modern CSS Reset

This repository contains a modern CSS reset inspired by Andy Bell's blog post on [Piccalilli](https://piccalil.li/blog/a-more-modern-css-reset/). The reset ensures cross-browser consistency by addressing common quirks and setting a solid foundation for styling.

## Features

- **Global Reset**: Removes default margin, padding, and sets `box-sizing` to `border-box` for all elements.
- **Box Sizing Rules**: Ensures `box-sizing` applies to pseudo-elements.
- **Font Size Adjustment Prevention**: Disables automatic text scaling on mobile browsers.
- **Margin Reset for Common Elements**: Provides better control over spacing for headings, paragraphs, and lists.
- **Accessible List Styling**: Removes default list styles for elements with `role="list"`.
- **Core Body Defaults**: Sets a minimum height, line height, and typography defaults for the body.
- **Balanced Text Wrapping**: Improves text wrapping for headings.
- **Form Element Inheritance**: Ensures inputs and buttons inherit font styles from the body.
- **Optimized Images**: Sets images and picture elements to be responsive and block-level by default.
- **Textarea Defaults**: Prevents overly small textareas.
- **Anchor Target Margin**: Adds scroll margin to elements targeted by `id`.

## Modifications

This repository includes an additional **simple global reset**:

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

This was added to ensure that all elements, by default, start with zero margin and padding for greater control in custom styling.

## Usage

To use this CSS reset in your project:

1. Copy the `reset.css` file into your project.
2. Import it at the top of your main stylesheet:

   ```css
   @import './reset.css';
   ```

3. Customize the reset file if needed for your specific use case.

## Attribution

The original reset code was authored by Andy Bell and published on [Piccalilli](https://piccalil.li/blog/a-more-modern-css-reset/). This repository includes the original reset with a minor addition (the global reset).

## License

The original reset code is provided under Andy Bell's licensing terms. Ensure compliance by visiting [Piccalilli](https://piccalil.li/blog/a-more-modern-css-reset/) for details.

This repository, including modifications, is licensed under the [MIT License](LICENSE).

