README.txt

rule 1:
read




steps tp get chat erver:
rule 1
get all of the 2.0 folder



# good cmd

openssl req -x509 -out localhost.crt -keyout localhost.key \
  -newkey rsa:2048 -nodes -sha256 \
  -subj '/CN=localhost' -extensions EXT -config <( \
   printf "[dn]\nCN=localhost\n[req]\ndistinguished_name = dn\n[EXT]\nsubjectAltName=DNS:localhost\nkeyUsage=digitalSignature\nextendedKeyUsage=serverAuth")

this needs to be ran on powershell / on the host

you nedd open ssl going to get going

ope!


