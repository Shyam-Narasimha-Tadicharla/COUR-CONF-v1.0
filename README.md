# Conference Expense Planner

A React-based web application for planning and calculating conference expenses with venue booking, add-ons selection, and meal planning capabilities.

## Features

🏢 **Venue Selection**
- Choose from multiple venue options
- Capacity-based room selection
- Real-time availability tracking
- Quantity limitations for premium venues

🎯 **Add-ons Management**
- Audio/Visual equipment selection
- Flexible quantity adjustments
- Cost calculation per item

🍽️ **Meal Planning**
- Per-person meal cost calculation
- Multiple meal option selection
- Dynamic pricing based on attendee count

💰 **Cost Tracking**
- Real-time total cost calculation
- Itemized expense breakdown
- Section-wise cost summaries

## Tech Stack

- **Frontend**: React 18+ with Hooks
- **State Management**: Redux Toolkit
- **Styling**: CSS3 with custom stylesheets
- **Icons**: HTML entities for UI elements

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/Shyam-Narasimha-Tadicharla/COUR-CONF-v1.0.git
cd COUR-CONF-v1.0
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser

## Project Structure

```
src/
├── components/
│   ├── ConferenceEvent.jsx    # Main component
│   ├── TotalCost.jsx          # Cost summary component
│   └── ConferenceEvent.css    # Styling
├── store/
│   ├── venueSlice.js          # Venue state management
│   ├── avSlice.js             # Add-ons state management
│   └── mealsSlice.js          # Meals state management
└── App.jsx                    # Root component
```

## Usage

1. **Select Venue**: Choose from available conference rooms and halls
2. **Add Equipment**: Select necessary AV equipment and add-ons
3. **Plan Meals**: Specify number of attendees and select meal options
4. **Review Costs**: Toggle to detailed view to see itemized expenses
5. **Calculate Total**: View real-time cost calculations across all categories

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.

## Author

**Shyam Narasimha Tadicharla**
- GitHub: [@Shyam-Narasimha-Tadicharla](https://github.com/Shyam-Narasimha-Tadicharla)

---

⭐ If you found this project helpful, please give it a star!