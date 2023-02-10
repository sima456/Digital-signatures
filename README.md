# Digital-signatures

usage: dig_scan.py [-h] [-g] [-s] [-v] [-m MESSAGE]
                   [-n NAME] [-c COUNTRY] [-e EMAIL]
                   [-o ORGANIZATION] [-k KEY]
                   [-si SIGNATURE]

Create and verify digital signatures

options:
  -h, --help            show this help message and
                        exit

  -g, --generate        Generate a new
                        private/public key pair

  -s, --sign            Sign a message

  -v, --verify          Verify a signature

  -m MESSAGE, --message MESSAGE
                        The message to sign or
                        verify

  -n NAME, --name NAME  The name of the signer

  -c COUNTRY, --country COUNTRY
                        The country of the signer

  -e EMAIL, --email EMAIL
                        The email of the signer

  -o ORGANIZATION, --organization ORGANIZATION
                        The organization of the
                        signer

  -k KEY, --key KEY     The private key (for
                        signing) or the public key
                        (for verifying)

  -si SIGNATURE, --signature SIGNATURE
                        The signature to verify

