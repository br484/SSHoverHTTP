# SSHoverHTTPS

Test to obfuscate https://github.com/jpillora/chisel

# Ofuscar 

  go install mvdan.cc/garble@latest

  git clone https://github.com/br484/SSHoverHTTP
  cd SSHoverHTTP

  env GOOS=windows GOARCH=amd64 ~/go/bin/garble build .
  env GOOS=linux GOARCH=amd64 ~/go/bin/garble build .
