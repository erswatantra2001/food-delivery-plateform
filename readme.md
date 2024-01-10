# EatEasy

EatEasy is your go-to platform for ordering food online from your favorite restaurants, hassle-free.

## Getting Started

These are the instructions to clone and run this project in your local machine for developement and testing purpose

### Prerequisites

- Node
- Git
- MongoDB

### Installation

1. First of all, Clone this repository & navigate to the directory

```
git clone https://github.com/erswatantra2001/food-delivery-plateform.git
cd Swigato
```

2. Install the Dependencies

```
npm install
```

### Running Locally

- First Create `.env` file in root directory using the following content and make changes if required.

```
PORT=8080
MONGO_URI="YourMongoDBuri"
TOKEN_SECRET="JwtSecret"
```

- Starting the Server

```
npm start
```

or

```
npm run dev
```

### Adding Food Items to Database Collection (Menu)

To add food items to database run

```
npm run menu
```

Edit `items.csv` file under `assets/csv` to change food items.