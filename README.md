run the html page in a browser, have the js file in the same dir. 




This SHA‑3 Hash Generator app uses the js‑sha3 library to create cryptographic hashes of any text you input. It supports several variants of the SHA‑3 family, each offering different output sizes and a corresponding number of unique possibilities:

    SHA3-512: Produces a 512‑bit hash
    
    SHA3-384: Produces a 384‑bit hash
    
    SHA3-256: Generates a 256‑bit hash
    
    SHA3-224: Yields a 224‑bit hash
    
    SHAKE128 (256‑bit output): This is an extendable‑output function (XOF) configured to produce a 256‑bit hash
    
    SHAKE256 (512‑bit output): Another XOF variant configured for a 512‑bit output

Input Text Limitations: The text area accepts any text encoded in UTF‑8. This means you can include letters, numbers, symbols, whitespace, and even emojis. There is no hard limit on the number of characters; however, extremely large inputs might affect performance based on your device and browser capabilities.

How the App Works: Simply type or paste your text into the input area, choose the desired hash algorithm from the dropdown menu, and click the "Generate Hash" button (or press Enter without Shift). The selected algorithm then processes your text using the js‑sha3 library, and the computed hash is displayed in the result section. Any errors (like missing input) are also handled gracefully.
