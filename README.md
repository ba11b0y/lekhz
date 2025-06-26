# lekhz

lekhz is a simple, minimalistic, and fast personal website template for Zola.
Ported from the Hugo theme [lekh](https://github.com/ba11b0y/lekh)

<img width="1470" alt="lekhz-dark" src="https://github.com/user-attachments/assets/811bcf6b-c29f-4977-b791-3ceb32b8f68e" />

## Contents

- [Installation](#installation)
- [Customization](#customization-options)

## Installation
First download this theme to your `themes` directory:

```bash
cd themes
git clone https://github.com/ba11b0y/lekhz.git
```
and then enable it in your `config.toml`:

```toml
theme = "lekhz"
```

## Customization options

Add the following to your `config.toml` file in the `[extra]` section:

```toml
[extra]
lekhz_name = "Rahul Tiwari"
lekhz_about = "About me description here"
lekhz_email = "jprrahultiwari@gmail.com"
lekhz_resume = "resume.pdf"
lekhz_post_limit = 3
lekhz_goatcounter_code = ""
# Example profiles configuration
lekhz_profiles = [
    { name = "GitHub", url = "https://github.com/ba11b0y" },
    { name = "Twitter", url = "https://x.com/ba11b0y" },
    { name = "LinkedIn", url = "https://www.linkedin.com/in/ba11b0y/" },
    { name = "Goodreads", url = "https://www.goodreads.com/user/show/91520565-rahul-tiwari"}
]
```
