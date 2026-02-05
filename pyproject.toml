[build-system]
requires = ["setuptools>=68", "wheel"]
build-backend = "setuptools.build_meta"

[project]
name = "WEALTH_PA_EE_MODELS"
version = "0.1.0"
description = "WEALTH physical activity and energy expenditure models and utilities"
readme = "README.md"
requires-python = ">=3.9"

# Add your main dependencies here
dependencies = [
    "numpy",
    "pandas",
    "scikit-learn",
    "joblib",
    "pygt3x"
]

authors = [
    { name = "Luis", email = "luis@example.com" }
]

license = { text = "MIT" }

classifiers = [
    "Programming Language :: Python :: 3",
    "Intended Audience :: Science/Research",
    "Topic :: Scientific/Engineering :: Medical Science Apps."
]

[tool.setuptools]
package-dir = { "" = "src" }

[tool.setuptools.packages.find]
where = ["src"]

# Include non-Python files inside the package
[tool.setuptools.package-data]
wealth_pa_ee_models = [
    "models/**/*",
    "sample_data/**/*",
    "**/*.csv",
    "**/*.json",
    "**/*.yaml",
    "**/*.yml",
    "**/*.txt",
    "**/*.pkl",
    "**/*.joblib",
    "**/*.h5",
    "**/*.pt"
]

# Ensure package data is included
[tool.setuptools.include-package-data]
value = true
