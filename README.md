# Important words first

# Swap
- swap file:
  - https://wiki.archlinux.org/index.php/Swap#Swap_file
  - |
    ```bash
    dd if=/dev/zero of=/swapfile bs=1M count=512
    chmod 600 /swapfile
    mkswap /swapfile
    swapon /swapfile
    ```

- swap list:
  - `swapon -s`

# Memory
- memory check usage:
  - http://www.cyberciti.biz/faq/linux-check-memory-usage/
  - `cat /proc/meminfo`
  - `free -m`
  - `top`
  - `htop`
