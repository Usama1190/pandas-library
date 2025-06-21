# 🐼 pandas

**pandas** is a fast, powerful, flexible, and easy-to-use open-source data analysis and data manipulation library built on top of the Python programming language.

## 📦 Installation

You can install pandas using pip:

```bash
pip install pandas
```

Or with conda:

```bash
conda install pandas
```

## 📚 Documentation

Official documentation:  
🔗 https://pandas.pydata.org/docs/

API Reference:  
🔗 https://pandas.pydata.org/pandas-docs/stable/reference/index.html

## 🚀 Getting Started

Example usage:

```python
import pandas as pd

# Create a DataFrame
df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [25, 30, 35],
})

print(df)
```

## 🔧 Features

- Fast and efficient DataFrame object for data manipulation.
- Tools for reading and writing data between in-memory data structures and different formats (CSV, Excel, SQL, JSON, etc.).
- Intelligent data alignment and labeled indexing.
- Powerful group by functionality for data aggregation and transformations.
- Time series functionality.
- Missing data handling.

## 🤝 Contributing

We welcome contributions!  
Check the contribution guide here:  
🔗 https://pandas.pydata.org/docs/dev/development/index.html

To set up pandas for development:

```bash
git clone https://github.com/pandas-dev/pandas.git
cd pandas
pip install -r requirements-dev.txt
```

## 🧪 Running Tests

To run the test suite:

```bash
pytest pandas
```

## 📄 License

pandas is licensed under the [BSD 3-Clause License](https://github.com/pandas-dev/pandas/blob/main/LICENSE).
