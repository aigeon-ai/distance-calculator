markdown
# Distance Calculator MCP Server

## Overview

The Distance Calculator MCP Server is a versatile tool designed to compute the distance between geographical points using their coordinates. This server can handle various scenarios, including calculating the distance between one-to-one points or one-to-many points, making it suitable for a wide range of applications.

## Features

- **Simple Distance Calculation**: Compute the distance between two specific points. This tool is perfect for straightforward use cases where only two coordinates are involved.
  
- **One to Many Distance Calculation**: Determine the distances from a single starting point to up to ten different endpoints. This is particularly useful for scenarios where you need to evaluate multiple routes or destinations from a single location.
  
- **One to One Distance Calculation**: Similar to the simple calculation but allows for a more detailed setup, including additional parameters.

## Tool Descriptions

### Simple

- **Function Name**: `Simple`
- **Description**: Calculates the distance between two specified points.
- **Parameters**:
  - `lat_1`, `long_1`: Latitude and Longitude of Point 1 (required).
  - `lat_2`, `long_2`: Latitude and Longitude of Point 2 (required).
  - `unit`: The unit of distance (optional, default is kilometers).
  - `decimal_places`: Number of decimal places in the result (optional, default is 16).

### One to Many

- **Function Name**: `One to Many`
- **Description**: Calculates the distance from one starting point to multiple endpoints (up to 10).
- **Parameters**:
  - `start_point`: Coordinates of the starting point (required).
  - `end_point_1` to `end_point_10`: Coordinates of end points (optional).
  - `unit`: The unit of distance (optional, default is kilometers).
  - `decimal_places`: Number of decimal places in the result (optional, default is 16).

### One to One

- **Function Name**: `One to One`
- **Description**: Calculates the distance between two points with more detailed configuration options.
- **Parameters**:
  - `start_point`: Coordinates of the starting point (required).
  - `end_point`: Coordinates of the end point (required).
  - `unit`: The unit of distance (optional, default is kilometers).
  - `decimal_places`: Number of decimal places in the result (optional, default is 16).

## Usage

The Distance Calculator MCP Server is intuitive and easy to use. Simply choose the appropriate tool for your needs and input the required parameters. The server will return the calculated distance based on the specified units and precision.

Feel free to explore the capabilities of the Distance Calculator MCP Server and discover how it can be tailored to meet your specific requirements. Whether you're planning a trip, analyzing logistics, or developing a location-based application, this server provides the tools you need to get accurate distance measurements.