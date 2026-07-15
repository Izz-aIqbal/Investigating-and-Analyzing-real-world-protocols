# Investigating-and-Analyzing-real-world-protocols

# Network Protocol Analysis

Wireshark-based analysis of HTTP, HTTPS, and QUIC protocols for Computer Networks coursework.

## Files
- `http-analysis-report.docx` - HTTP traffic analysis
- `https-analysis-report.docx` - HTTPS/TLS analysis  
- `quic-analysis-report.docx` - QUIC protocol analysis

## Analysis Summary

### HTTP Analysis
- Captured plaintext HTTP traffic from neverssl.com
- Analyzed GET/POST requests, headers, and responses
- Confirmed connection persistence (keep-alive)
- Identified 10 HTTP response messages

### HTTPS Analysis
- Examined TLS 1.2 handshake with cap1.grammarly.com
- Extracted server certificate and cipher suite information
- Confirmed application data encryption post-handshake

### QUIC Analysis
- Studied QUIC Version 1 implementation via Google services
- Analyzed embedded TLS 1.3 handshake
- Compared 1-RTT vs 0-RTT connection establishment
- Documented HTTP/3 vs HTTP/2 differences

## Key Findings
- HTTP: Plaintext, vulnerable to interception
- HTTPS: TLS encryption protects data confidentiality
- QUIC: UDP-based, faster connection setup, built-in encryption

## Tools
- Wireshark with filters: `http`, `tls`, `quic`

- IZZA IQBAL


---
