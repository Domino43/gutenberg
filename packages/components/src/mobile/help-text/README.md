# HelpText

Renders a help text shell with a ExternalLink appended at the end.

## Usage

```jsx
import { HelpText } from '@wordpress/components';

const HelpfulText = () => (
	<HelpText url="https://wordpress.org" moreLinkText="Learn More">WordPress is an easy to use publishing tool</HelpText>
);
```

## Props

The text that's displayed within the component's tags will be "clickable" and extenal link will be added at the end.

### `url`

An optional URL that is being linked to and will open in a new window when tapped or clicked.

-   Type: `String`
-   Required: No

### `moreLinkText` 

An optional Text as the click abel text at the end.

-   Type: `String`
-   Required: No
