# pcap2sipp

Convert a SIP pcap capture into a runnable SIPp UAC scenario — entirely
in the browser. Nothing is uploaded anywhere; the CSP `connect-src 'none'`
in the page makes that enforceable.

**Live:** https://<username>.github.io/pcap2sipp/

## Usage

Open the link, drop a `.pcap` / `.pcapng`, review the flow and generation
notes, download the resulting `scenario.xml`.

## Limits

UDP/TCP SIP only, no TLS. One call per file. See the "What gets templated"
panel on the page for details.