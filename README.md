# Mayavi-3body-simulation
# pyproject.toml

[build-system]
requires = ["setuptools>=61.0"]
build-backend = "setuptools.build_meta"
backend-path = ["."]

[project]
name = "mayavi-3body-simulation"
version = "0.1.0"
description = "An advanced 3D simulation of the three-body problem using Mayavi with a direct pipeline approach, featuring particle dust and prismatic tracers."
readme = "README.md"
requires-python = ">=3.8"
license = { text = "MIT License" } # Or specify { file = "LICENSE.txt" } if you add one
authors = [
    { name = "Aylos9er", email = "your.email@example.com" }, # Replace with actual email if desired
]
keywords = ["3d simulation", "n-body", "three-body problem", "mayavi", "vtk", "physics simulation", "scientific visualization", "astrophysics"]

dependencies = [
    "numpy>=1.20",
    "mayavi>=4.7.0",
    # PyQt5 or PySide2 might be needed if not pulled in by Mayavi,
    # but usually Mayavi handles its GUI backend dependency.
    # e.g., "PyQt5"
]

[project.urls]
"Homepage" = "https://github.com/Aylos9er/Mayavi-3body-simulation"
"Bug Tracker" = "https://github.com/Aylos9er/Mayavi-3body-simulation/issues"

classifiers = [
    "Development Status :: 3 - Alpha",
    "Intended Audience :: Developers",
    "Intended Audience :: Education",
    "Intended Audience :: Science/Research",
    "License :: OSI Approved :: MIT License",
    "Natural Language :: English",
    "Operating System :: OS Independent", # Mayavi itself has some OS considerations for installation
    "Programming Language :: Python :: 3",
    "Programming Language :: Python :: 3.8",
    "Programming Language :: Python :: 3.9",
    "Programming Language :: Python :: 3.10",
    "Programming Language :: Python :: 3.11",
    "Programming Language :: Python :: 3.12",
    "Topic :: Scientific/Engineering :: Physics",
    "Topic :: Scientific/Engineering :: Visualization",
    "Topic :: Multimedia :: Graphics :: 3D Rendering",
]
