# AI Coding Tutor

An interactive AI-powered coding tutor designed to help users learn programming concepts through personalized instruction and real-time feedback.

## Features

- **Interactive Learning**: Provides hands-on coding exercises.
- **Real-time Feedback**: Offers immediate feedback on your code.
- **Personalized Lessons**: Adapts to the user's learning pace and skill level.
- **User-friendly Interface**: Built with Streamlit for an intuitive and engaging experience.

---

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.8 or higher
- pip (Python package installer)

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/ai-coding-tutor.git
   cd ai-coding-tutor
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the Virtual Environment**:
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - On **Mac/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install Required Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## Running the Application

The application consists of two main components: the Parlant server and the Streamlit frontend. Follow these steps to get started:

1. **Start the Parlant Server**:
   ```bash
   parlant-server --module "service"
   ```

2. **Run the Streamlit Frontend**:
   Open a new terminal, activate the virtual environment again, and execute:
   ```bash
   streamlit run Home.py
   ```

3. **Access the Application**:
   Visit the link provided in the terminal to interact with the AI Coding Tutor.

---

## Contributing

We welcome contributions! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a meaningful message"
   ```
4. Push the changes:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

 

 