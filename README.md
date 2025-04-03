# Documentation

## Tech Stack
View our complete [tech stack documentation](docs/getting-started/tech-stack.md) to understand our technology choices and implementation strategy.

# Installation

Follow these steps to set up MkDocs and get your documentation site running locally.

## Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

## Step 1: Create a Virtual Environment (Recommended)

It's best practice to use a virtual environment to avoid conflicts between projects:

### On Windows

```bash
# Navigate to your project directory
cd your-project-directory

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
venv\Scripts\activate
```

### On macOS/Linux

```bash
# Navigate to your project directory
cd your-project-directory

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
source venv/bin/activate
```

You'll know the virtual environment is active when you see `(venv)` at the beginning of your command prompt.

## Step 2: Install MkDocs

With your virtual environment activated, install MkDocs using pip:

```bash
pip install mkdocs
```

## Step 3: Install the Material Theme

We recommend using the Material for MkDocs theme, which provides a beautiful, responsive design:

```bash
pip install mkdocs-material
```

## Step 4: Install Additional Plugins

For optimal functionality, install the following plugins:

```bash
pip install mkdocs-minify-plugin
```

Alternatively, you can install all dependencies at once using the provided requirements.txt file:

```bash
pip install -r requirements.txt
```

## Step 5: Clone or Download This Repository

If you haven't already, get the repository:

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

## Step 6: Run the Development Server

Start the local development server to preview your documentation:

```bash
mkdocs serve
```

Your documentation site should now be available at [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Next Steps

Now that you have MkDocs installed and running, head over to the [Quick Start Guide](quick-start.md) to learn how to create and edit your documentation.