## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Follow these simple steps to set up your environment.

### Prerequisites

Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/). This project was developed using Python 3.x.

### Cloning the Repository

First, clone the repository to your local machine:

```bash
git clone https://your-repository-url-here.git
cd your-project-directory
```

### Setting Up the Virtual Environment

To isolate and manage the project dependencies, you should create a virtual environment. Run the following commands to create and activate a virtual environment:

#### For Windows

```bash
python -m venv env
env\Scripts\activate
```

#### For macOS and Linux

```bash
python3 -m venv env
source env/bin/activate
```

### Installing Dependencies

With the virtual environment activated, install the project dependencies by running:

```bash
pip install -r requirements.txt
```

### Configuring Environment Variables

The project uses environment variables for configuration to keep sensitive information out of the source code. You need to create a `.env` file in the root of your project directory with the necessary variables:

1. Create a new file named `.env` in the root of your project.
2. Open the `.env` file and add the following lines, replacing the placeholder values with your actual database credentials and configurations:

```
DBNAME=your_database_name
USER=your_database_user
PASSWORD=your_database_password
HOST=your_database_host
```

Make sure to save the file once you have entered the correct information.

### Running the Application

With the environment set up and the configurations in place, you can now run the application:

```bash
python script.py
```

Follow any additional setup or runtime instructions specific to the application.

### Deactivating the Virtual Environment

When you're done working on the project, you can deactivate the virtual environment by simply running:

```bash
deactivate
```

(on both Windows and Unix-based systems).
