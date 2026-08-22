# 💰 Personal Finance Management System

A modern, user-friendly full-stack application for tracking daily income and expenses with comprehensive analytics, budgeting, and reporting features.

## ✨ Features

### 📊 Dashboard
- Real-time financial overview
- Total income, expenses, and current balance
- Today's, weekly, and monthly summaries
- Recent transactions list
- Interactive charts and graphs
- Income vs expense visualization
- Monthly spending trends
- Category-wise expense breakdown

### 💵 Income & Expense Management
- Easy-to-use forms for adding income and expenses
- Multiple categories for both income and expenses
- Various payment methods support (Cash, Bank, UPI, Cards)
- Edit and delete transactions
- Transaction descriptions and notes
- Optional receipt/bill attachments

### 🔍 Transaction Management
- View all transactions in a clean table/list
- Filter by income/expense type
- Filter by category
- Filter by payment method
- Filter by date range
- Search functionality
- Sort by date and amount
- Detailed transaction information

### 📈 Reports & Analytics
- Daily, weekly, monthly, and yearly reports
- Category-wise expense analysis
- Income vs expense comparisons
- Savings analysis
- Interactive charts and graphs
- Exportable reports

### 💳 Budget Management
- Set monthly budgets
- Category-wise budget allocation
- Real-time budget tracking
- Progress indicators
- Alerts at 80% and 100% budget utilization
- Budget vs actual comparison

### 🔄 Recurring Transactions
- Automate salary income
- Set recurring expenses (rent, bills, subscriptions)
- Support for daily, weekly, monthly, and yearly recurrence
- Easy management and modification

### 💾 Export & Backup
- Export transactions to Excel/CSV
- Generate PDF reports
- Full data backup functionality
- Data restore capability

### 🤖 AI Financial Assistant (Optional)
- Natural language queries
- Spending insights and recommendations
- Comparative analysis
- Smart expense reduction suggestions

### 🎨 User Interface
- Professional, clean design
- Fully responsive (mobile-first)
- Light and dark mode support
- Smooth animations
- Intuitive navigation
- Confirmation dialogs for critical actions

## 🛠️ Tech Stack

### Backend
- **Node.js & Express.js** - Server and API
- **TypeScript** - Type safety
- **MongoDB & Mongoose** - Database and ODM
- **JWT** - Authentication
- **Multer** - File uploads
- **XLSX & PDFKit** - Export functionality

### Frontend
- **React** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Chart.js** - Charts and graphs
- **React Query** - Data fetching
- **Zustand** - State management
- **React Router** - Navigation

## 📋 Prerequisites

- Node.js 16+
- MongoDB 4.4+
- npm or yarn

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/armytaxm-collab/personal-finance-manager.git
cd personal-finance-manager
```

### 2. Install dependencies
```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd client
npm install
cd ..
```

### 3. Setup environment variables
```bash
cp .env.example .env
# Edit .env with your configuration
```

### 4. Start MongoDB
```bash
mongod
```

### 5. Run the application

#### Development mode (Terminal 1)
```bash
npm run server
```

#### Frontend (Terminal 2)
```bash
npm run client
```

The application will be available at `http://localhost:3000`

## 📁 Project Structure

```
personal-finance-manager/
├── src/
│   ├── models/              # MongoDB schemas
│   ├── controllers/         # Route controllers
│   ├── routes/              # API routes
│   ├── middleware/          # Custom middleware
│   ├── services/            # Business logic
│   ├── utils/               # Utility functions
│   ├── types/               # TypeScript types
│   └── server.ts            # Express server
├── client/
│   ├── src/
│   │   ├── components/      # React components
│   │   ├── pages/           # Page components
│   │   ├── store/           # Zustand store
│   │   ├── hooks/           # Custom hooks
│   │   ├── services/        # API services
│   │   ├── types/           # TypeScript types
│   │   └── App.tsx          # Root component
│   └── package.json
├── .env.example             # Environment template
├── package.json             # Dependencies
└── README.md                # This file
```

## 🔐 Security Features

- Secure password hashing with bcryptjs
- JWT-based authentication
- Input validation and sanitization
- CORS protection
- Rate limiting (recommended)
- Secure file upload handling
- SQL injection prevention
- XSS protection

## 📊 Income Categories

- Salary
- Business
- Freelance
- Interest
- Investment
- Other

## 🏷️ Expense Categories

- Food
- Shopping
- Transport
- Electricity
- Rent
- Mobile/Internet
- Medical
- Education
- Entertainment
- Business
- Household
- Other

## 💳 Payment Methods

- Cash
- Bank Account
- UPI
- Credit Card
- Debit Card
- Other

## 🌍 Localization

- **Currency**: Indian Rupee (₹)
- **Date Format**: DD/MM/YYYY
- **Language**: English (Extensible)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🧪 Testing

```bash
# Run tests
npm test

# Run with coverage
npm test -- --coverage
```

## 📝 Sample Data

The application includes a seed script to populate demo data for testing:

```bash
npm run seed
```

## 🐛 Known Issues

None currently. Please report issues on GitHub.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 💡 Future Enhancements

- [ ] Multi-currency support
- [ ] Mobile app (React Native)
- [ ] Advanced AI recommendations
- [ ] Investment portfolio tracking
- [ ] Bill reminders and notifications
- [ ] Collaborative finances (family budget)
- [ ] Bank integration
- [ ] Tax calculation assistance
- [ ] Social features

## 📞 Support

For support, email armytaxm@example.com or open an issue on GitHub.

## 🙏 Acknowledgments

- Built with modern web technologies
- Inspired by leading finance apps
- Community feedback and contributions

---

**Made with ❤️ by armytaxm-collab**
