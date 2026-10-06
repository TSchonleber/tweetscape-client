# tweetscape client bundle
Gzip containers of the RuneScape Classic web client (2003scape/rsc-c, AGPL-3.0, software renderer build)
served via jsDelivr as the fallback when the X-hosted image payloads are unavailable.
Format: 'RSCB' u8 count, then per file u16 nameLen, name, u32 len, bytes.
