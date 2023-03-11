3.11.2023

- hostgator DNS changes:
  - apex domain A record
    - original: matthewstockinger.com A 50.87.145.3
    - new: matthewstockinger.com A 75.2.60.5
    - got error message that there were duplicate CNAME records for cpanel.matthewstockinger.com and webmail.matthewstockinger.com. Deleted those.
  - www subdomain CNAME record
    - original: www.matthewstockinger.com CNAME matthewstockinger.com
    - new: www.matthewstockinger.com CNAME velvety-clafoutis-ed86a1.netlify.app
