# Earth's Inner Secrets Dataset

## Description
This dataset contains 20 fascinating scientific facts about Earth's internal structure, processes, and phenomena. The data is structured in JSON format and covers various categories including the Earth's core, magnetic field, geology, hydrology, and more.

## Data Structure
The dataset is organized as a JSON object with the following structure:
- `earthInnerSecrets`: Array of fact objects
  - `id`: Unique identifier (1-20)
  - `fact`: Detailed description of the Earth-related fact
  - `category`: Classification of the fact (e.g., Core, Geology, Hydrology)

## Categories Covered
- Core
- Magnetic Field
- Hydrology
- Structure
- Geology
- Physics
- Biology
- Chemistry
- Composition
- Research

## Usage
The data can be loaded and parsed as a standard JSON file. Example:
```json
{
  "earthInnerSecrets": [
    {
      "id": 1,
      "fact": "...",
      "category": "..."
    }
  ]
}
