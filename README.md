# AXOON_FD_07
This project is a modern responsive card layout built using HTML and Tailwind CSS, showcasing interactive shoe product cards with stylish hover effects. The layout is structured into a full-screen flex container that holds four individual product cards, each representing a shoe with detailed pricing and icon interactions.

🧩 Key Features:
Responsive Flex Layout:

The cards are arranged horizontally using Tailwind’s flex and gap utilities.

The container centers content both vertically and horizontally with items-center justify-center.

Product Cards:

Each card is styled with rounded corners (rounded-2xl), padding, and a light slate background.

Cards are assigned equal widths (w-3/12) and a fixed height (h-64) for consistency.

Interactive Hover Effects:

Shoe Image Animation: On hover, the shoe image rotates slightly and translates to give a dynamic feel using group-hover:rotate-20 and group-hover:translate-4.

Sliding Label: A black vertical bar with rotated shoe name (AIR ZOOM PEGASUS) slides in smoothly from the left using group-hover:translate-x-0.

Icon Compression: The bottom row with icons and pricing slides inward on hover (group-hover:translate-x-10, group-hover:pr-8), making space for the black strip.

Price Display:

The card displays both the original price (strikethrough) and the discounted price, styled appropriately with Tailwind utility classes.

Icons:

Includes a heart icon (wishlist) and shopping cart icon, both of which highlight (hover:text-red-400) on hover.

Group Hover Control:

All hover effects are handled elegantly using Tailwind’s group and group-hover utility classes for better state-based styling.

🔧 Technologies Used:
HTML5

Tailwind CSS 
