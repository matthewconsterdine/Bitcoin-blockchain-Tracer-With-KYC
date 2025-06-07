# Bitcoin Blockchain Tracer With KYC 

[![](/report/images/application.png)](https://consto.uk/blockchain-tracer)

This was my graduation project, and in 2025, I improved the algorithm by adding the functionality to automatically link KYC addresses.

This project demonstrates the ability to visualize, and trace transactions through the Bitcoin network, evaluating three different methods. Namely poison, haircut and First-In-First-Out (FIFO).

I wrote the UI in Python and wrapped it with Swift code. Run 'blockchain-tracer --help' in your Mac terminal. a UI was created to first build up a network graph representing Bitcoin addresses as nodes, and transactions as directional edges. This allows the user to easily grasp the history of any given Bitcoin address, and then trace any transaction either up or down the graph.

Give it enough time to run; it can help track the associated address of suspicious tokens, even if they've been through a mixer. I used an algorithm to highlight suspicious transactions that obscure their origins.

## For users who have had their BTC stolen, it's worth a try. Tracing suspicious BTC addresses back to known source or any KYC-verified addresses might help in recovering the stolen Bitcoin. At least find someone who's responsible. Run 'blockchain-tracer --FindKYC <addr>' in your terminal.

By clicking on a node in the graph, the application will automatically load that address and it's associated transactions, adding it to the graph. By hovering over a node in the graph, the tool-tip on the right will appear. It displays a number of useful statistics about the address, and gives the user the option to trace transactions by clicking on any of the colourful buttons.

* [Try online](https://consto.uk/blockchain-tracer)
* [Read the report](/report.pdf)

# Contributing

Welcome contributions to enhance the functionality and performance of the Bitcoin Blockchain Tracer. Please feel free to submit issues, feature requests, or pull requests.
License

# This project is licensed under the MIT License. See the LICENSE file for more details.
