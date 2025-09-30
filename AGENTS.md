# Project Maintenance Guide

This guide is designed for AI agents to understand the structure of the succulent care project files and how to maintain the project. It outlines each file's purpose, content structure, and maintenance procedures for common operations like adding a new plant.

## Project File Structure

### 1_plant_collection_overview.md
- **Purpose**: Comprehensive overview of the current plant collection, including species, acquisition details, and current status.
- **Content Structure**:
  - Plant listings with species names, quantities, and descriptions
  - Acquisition dates and sources
  - Current health status and notes
- **Maintenance Notes**: Update when adding/removing plants or changing plant status.

### 2_plant_history_timeline.md
- **Purpose**: Chronological record of plant-related events, growth milestones, and care history.
- **Content Structure**:
  - Timeline entries with dates
  - Events like watering, repotting, propagation
  - Growth observations and measurements
- **Maintenance Notes**: Add entries for new events; review periodically for patterns.

### 3_care_maintenance_details.md
- **Purpose**: Detailed care instructions and maintenance schedules for different plant types.
- **Content Structure**:
  - Care profiles by species or group
  - Watering, lighting, soil, and fertilization requirements
  - Seasonal adjustments and troubleshooting
- **Maintenance Notes**: Update when new care information is discovered or plant needs change.

### 4_placement_locations.md
- **Purpose**: Documentation of available placement locations in the home, including light conditions and space details.
- **Content Structure**:
  - Location descriptions (e.g., windowsills, balconies)
  - Light levels, orientation, and seasonal variations
  - Space dimensions and constraints
- **Maintenance Notes**: Update if locations change (e.g., new furniture, seasonal light shifts).

### 5_current_placement_plan.md
- **Purpose**: Current assignment of plants to locations, with rationale and optimization notes.
- **Content Structure**:
  - Plant-to-location mappings
  - Light requirement matches
  - Notes on seasonal adjustments and space utilization
- **Maintenance Notes**: Revise when plants are moved or new placements are optimized.

### 6_project_goals_context.md
- **Purpose**: Overall project goals, personal context, challenges, and success criteria.
- **Content Structure**:
  - Project overview and primary goals
  - Personal experience level and location details
  - Challenges and success metrics
- **Maintenance Notes**: Update as goals evolve or new challenges arise.

### 7_geolocation_data.md
- **Purpose**: Geographic and climatic data relevant to plant care.
- **Content Structure**:
  - Location coordinates and climate zone
  - Seasonal weather patterns
  - Local environmental factors
- **Maintenance Notes**: Update if location changes or new data becomes available.

## Maintenance Procedures

### Adding a New Plant to the Collection
1. **Update Plant Collection Overview** (`1_plant_collection_overview.md`):
   - Add a new entry with species name, quantity, acquisition date, source, and initial description.
   - Include any identification notes if the species is uncertain.

2. **Update Placement Plan** (`5_current_placement_plan.md`):
   - Determine optimal location based on light requirements and available spaces.
   - Assign the plant to a location and document the rationale.
   - Consider seasonal adjustments and space constraints.

3. **Record History Entry** (`2_plant_history_timeline.md`):
   - Add an acquisition entry with date, source, and initial observations.
   - Note initial health status and potting details.

4. **Check Project Goals** (`6_project_goals_context.md`):
   - Ensure the addition aligns with overall project objectives.
   - Update success criteria if necessary (e.g., new identification goals).

### Seasonal Maintenance
1. **Review Placement** (`5_current_placement_plan.md`, `4_placement_locations.md`):
   - Assess seasonal light changes and adjust plant locations as needed.
   - Update location data for current season.

2. **Update Care Schedules** (`3_care_maintenance_details.md`):
   - Modify watering and care routines based on seasonal climate data.
   - Reference geolocation data for accuracy.

3. **Log Seasonal Events** (`2_plant_history_timeline.md`):
   - Record seasonal transitions, growth spurts, or dormancy periods.

### Health Monitoring and Updates
- Regularly update plant status in `1_plant_collection_overview.md`.
- Add health observations to `2_plant_history_timeline.md`.
- Adjust care details in `3_care_maintenance_details.md` based on observed results.

## AI Agent Guidelines
- Always cross-reference related files when making updates.
- Maintain consistent formatting and metadata (e.g., keywords, related files).
- Prioritize data accuracy and cite sources for care information.
- Suggest optimizations that align with project goals in `6_project_goals_context.md`.
