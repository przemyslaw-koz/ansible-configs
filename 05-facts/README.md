ansible all -m setup -- wyswietla wszystkie zgromadzone fakty na temat hostów

ansible all -m setup -a 'filter=ansible_all_ipv6_addresses' - można filtrować fakty, poniewż zazwyczaj ta lista jest bardzo długa

