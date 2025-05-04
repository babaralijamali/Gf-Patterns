# Gf-Patterns
Updated GF Patterns for (SSRF, RCE, LFI, SQLi, SSTI, IDOR, URL Redirection, Debug Logic, and Interesting Subdomains) - Parameters Grep

# Gf-Patterns

## [GF](https://github.com/tomnomnom/gf) By [![Twitter](https://img.shields.io/badge/twitter-@TomNomNom-blue.svg)](https://twitter.com/TomNomNom)

A wrapper around grep, to help you grep for things

# Installation
git clone https://github.com/babaralijamali/Gf-Patterns

# To get started quickly:
mkdir ~/.gf
#
mv ~/Gf-Patterns/*.json ~/.gf

# Use Example
cat subdomains.txt | waybackurls | sort -u >> waybackdata | gf ssrf | tee -a ssrfparams.txt
#
cat waybackdata | gf redirect | tee -a redirect.txt
