# Bits of Security

An interactive educational tool to build intuitive understanding of cryptographic keyspace sizes and brute-force resistance.

## How it works

Cryptographic security relies on the exponential growth of the search space as key length (in bits) increases. This tool visualizes a binary key register, allowing you to run a simulated brute-force attack at different rates (measured in bits of entropy searched per second).

- **Odometer Effect**: At low speeds, you can see the binary odometer counting up sequentially.
- **Visual Blur**: Bits that flip faster than 30 Hz are randomized to simulate active visual spinning.
- **Time to Exhaust Space**: Calculates the average time required to locate a key (50% of the space) and exhaust the full keyspace (100% of the space), anchoring vast time frames in comparison to the age of the universe.
- **Interactive Controls**: Hold the `Arrow Up` and `Arrow Down` keys globally to adjust brute-force speeds smoothly.

## Live Demo

This project is hosted on GitHub Pages:
[https://bohemian-miser.github.io/bits-of-security/](https://bohemian-miser.github.io/bits-of-security/)
