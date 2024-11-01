# Traffic Data Analysis

This project analyzes network traffic data to provide insights into protocol distributions, traffic patterns, key statistics and also the anomalies from captured packets. The analysis includes visualization of traffic frequency, average packet length, and identification of prominent IP addresses in DNS requests and responses.

## Features

- **Protocol Analysis**: Extracts and summarizes protocol usage, including the frequency and average packet length of different network protocols.
- **DNS Traffic Insight**: Calculates DNS request and response statistics, such as the average length of requests/responses and frequency of occurrences.
- **IP Address Lookup**: Identifies the most frequently contacted IP addresses, resolving them to hostnames where possible.
- **Device Information**: Displays the IP address of the device from which the traffic was captured.
- **Protocol Distribution**: Determines and visualizes which protocol has the highest number of packets, along with the average packet length.
- **Interactive Visualizations**: Provides polar chart visualizations to compare frequency and average packet length across various protocols.

## Installation

To run this notebook, ensure you have Python 3.x and install the following dependencies**:

```bash
pip install -r requirements.txt
```

## Usage
Automatically generate details and visualizations for your WireShark packet capture by changing the *df* variable path with your file.

## Contributing
Contributions to this project are welcome. Please fork the [repository](https**://github.com/RampageousRJ/Network-Traffic-Analysis) and submit a pull request with your changes.
