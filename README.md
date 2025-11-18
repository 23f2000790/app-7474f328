# NeonWallet: Cyberpunk Personal Finance Dashboard

NeonWallet is a futuristic web application designed to help you manage your personal finances with a striking cyberpunk aesthetic. It provides a simple yet interactive dashboard to track your income and expenses, monitor your budget, and persist your financial data.

## Features

*   **Cyberpunk Visuals:** A deep dark `slate-950` background with vibrant neon cyan and hot pink accents creates an immersive, futuristic feel. Glassmorphism effects are applied to transaction cards for a sleek, transparent look.
*   **Massive Balance Display:** Your total balance is prominently displayed at the top with a large, glowing counter, making it easy to see your financial standing at a glance.
*   **Expense Logging Form:** A user-friendly form allows you to quickly add new transactions, specifying the name, amount, and type (Income or Expense).
*   **Dynamic Transaction List:** As you add transactions, they appear instantly in a scrollable list below the form. Income entries are highlighted in neon green, while expenses are marked in neon red.
*   **Monthly Budget Progress:** A CSS-based progress bar visually represents your "Monthly Budget Used" against a predefined budget of $2000, helping you stay on track.
*   **Data Persistence:** All your transactions are automatically saved to your browser's LocalStorage, ensuring your data remains intact even after refreshing the page.
*   **Interactive Deletion:** Each transaction in the list comes with a convenient "Delete" button (trash icon), allowing you to remove entries and instantly update your total balance and budget.

## Technologies Used

*   **HTML5:** Structure of the web application.
*   **Tailwind CSS:** For all styling, providing a utility-first approach and enabling the distinct cyberpunk theme.
*   **JavaScript (Vanilla):** Powers all interactive elements, dynamic data handling, and LocalStorage integration.
*   **Font Awesome:** For the trash can icon.

## How to Run

1.  **Save the files:** Save the `index.html` file to your local machine.
2.  **Open in Browser:** Open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Edge).
3.  **Start Managing:** Begin adding your income and expenses, and watch your NeonWallet come to life!

Your transactions will be saved automatically in your browser's LocalStorage. If you clear your browser's data, your transactions will be lost.

## Screenshot (Conceptual)

Imagine a dark interface with glowing text elements.
The "NeonWallet" title in bright fuchsia.
A large, cyan-glowing "$1,234.56" for total balance.
Input fields with subtle cyan borders on focus.
Transaction cards with a translucent, blurred background and a thin white border, with a vibrant green or red left border indicating income or expense.
A progress bar in deep red for budget usage.