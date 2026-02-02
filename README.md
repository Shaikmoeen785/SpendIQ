🛒 SpendIQ: Scan, Track, and Pay Smarter
Live Demo → https://spendiqpro.vercel.app/login

SpendIQ is a modern web application that transforms the retail experience. By enabling real-time barcode scanning, instant budget tracking, and queue-free payments directly from a smartphone, it empowers both shoppers and businesses.

The Problem: An Outdated Shopping Experience
In today's fast-paced world, the traditional shopping process is slow, inefficient, and often frustrating.

Manual Tracking: Shoppers struggle to manually track expenses, often leading to overspending.

Lack of Information: Getting instant product details while shopping is difficult.

Wasted Time: Standing in long checkout queues is a major point of friction and wastes valuable time.

Complex Tools: Existing budgeting apps are often too complex, lack real-time scanning, or don't integrate payments, making them impractical for in-store use.

Our Solution: A Seamless Scan-and-Go System
SpendIQ addresses these pain points with an intuitive, all-in-one web application that streamlines the entire shopping journey.

✅ How We Solved It
Instant Barcode Scanning: We integrated the ZXing Library with the WebRTC API to turn any smartphone camera into a high-accuracy (95%) barcode scanner.

Real-Time Budgeting: A dynamic, 60 FPS animated progress bar gives users immediate visual feedback on their spending, making it easy to stay within budget.

Persistent Shopping Cart: By using LocalStorage, the app remembers a user's cart, even if the browser is closed and reopened.

Queue-Free Payments: An integrated online payment gateway allows users to pay for their items instantly and leave, completely bypassing the checkout line.

Accessibility First: The app is WCAG-compliant, ensuring it's usable by everyone, including people with disabilities.

🛠️ Technology We Used
This project was built with a focus on a fast, reliable, and entirely client-side experience, requiring no backend setup.

Core: HTML5, CSS3, Vanilla JavaScript

Barcode Scanning: ZXing Library & WebRTC MediaDevices API

Data Handling: Fetch API to pull product data from JSONBin

Client-Side Storage: Browser LocalStorage API

User Interface: Smooth animations powered by CSS Transitions and requestAnimationFrame

The Outcome: A Win-Win for Customers and Businesses
SpendIQ delivers tangible benefits that enhance the shopping experience and improve operational efficiency.

🌟 What This Project Solved
SpendIQ successfully eliminates the most frustrating parts of shopping. It gives consumers control over their budget and time, while providing businesses with a tool to reduce congestion and improve customer flow.

📈 Impact and Benefits
For Customers:

Time Saved: Eliminates waiting in checkout lines.

Financial Control: Prevents overspending with live budget tracking.

Convenience: Provides a seamless, all-in-one shopping tool right in the browser.

For Business Owners:

Increased Efficiency: Reduces checkout congestion and frees up staff.

Improved Sales: A smoother experience encourages customers to complete purchases.

Enhanced Satisfaction: A modern, hassle-free process leads to happier, more loyal customers.

🔮 Future Roadmap
The vision for SpendIQ includes:

Cloud Sync & User Accounts: For a personalized experience across devices.

AI-Powered Price Insights: To help users make smarter purchasing decisions.

Advanced Expense Analytics: A dashboard for tracking spending habits over time.
