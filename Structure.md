# Project Structure

## Concepts
As a UI framework designed to be used with vue.js and tailwindcss the expectation of tight coupeling is to be understood. However, all of the components within the UI framework should be easily customizable and useable without the rest of the framework. Some util dependencies are inevitable but they as well should be packageable to be used seperatly from the rest of the framework as much as possible.
For this reason configuration plays a key role in the overall structure and inclusion of components as well as ovveridding of defaults. THe concept is that sane defaults are provided depending on the context of use and may be ovverridden at any time.

## Divisions