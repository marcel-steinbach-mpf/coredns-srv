# Example CoreDNS external service SRV record

1. Install CoreDNS (download and extract from https://github.com/coredns/coredns/releases/tag/v1.6.9)


2. Start   
    ```
    git clone https://github.com/marcel-steinbach-mpf/coredns-srv.git
    cd coredns-srv
    $PATH_TO_COREDNS/coredns
    ```
3. Try:
    ```
    dig -t SRV okta.internal  @localhost
    ```
