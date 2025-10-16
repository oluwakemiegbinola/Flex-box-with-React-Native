# Flex-box-with-React-Native
React Native helps you build real native mobile apps faster, using the same React skills you’d use for web development — but running directly on iOS and Android.
React Native lets you write components using React syntax (like <View>, <Text>, and <Image>) that are actually translated into real native UI elements, not web views. So your app looks and feels like a real native app — fast and responsive.

Key things to know:

It uses JavaScript (or TypeScript) with React concepts like state, props, and components.

You can use native modules when you need deeper access to platform features (like camera, GPS, Bluetooth, etc.).

Styling is done with a Flexbox-like layout, similar to CSS, but tailored for mobile.

You can hot reload your code, meaning you see your changes instantly without rebuilding the app.
Here’s the quick breakdown:

Default:
flexDirection: 'column' → items go vertically.

If you want horizontal layout:
You set flexDirection: 'row' → items go side by side (left to right).
flex: This property on an individual item determines how much space it occupies within its parent container. A flex: 1 means the item will stretch to fill available space, sharing it equally with other items also having flex: 1. Different flex values can be used to proportionally control item sizes.
flexDirection: Controls the direction of the main axis (and the perpendicular cross axis) for children items within a container.
'column' (default): Arranges items vertically.
'row': Arranges items horizontally.
justifyContent: Controls the alignment of items along the main axis.
'flex-start' (default): Items are packed towards the start of the main axis.
'flex-end': Items are packed towards the end of the main axis.
'center': Items are centered along the main axis.
'space-between': Items are evenly distributed with space between them.
'space-around': Items are evenly distributed with equal space around them.
alignItems: Controls the alignment of items along the cross axis.
'stretch' (default): Items stretch to fill the container along the cross axis.
'flex-start': Items are aligned to the start of the cross axis.
'flex-end': Items are aligned to the end of the cross axis.
'center': Items are centered along the cross axis.
'baseline': Items are aligned based on their baselines.
alignSelf: Allows individual items to override the alignItems property of their parent container.
flexWrap: Controls whether flex items are forced onto a single line or can wrap onto multiple lines.
'nowrap' (default): All items are on one line.
'wrap': Items wrap onto multiple lines if necessary.
alignContent: Controls the alignment of flex lines within a multi-line flex container along the cross axis. This property is only effective when flexWrap is set to 'wrap'.