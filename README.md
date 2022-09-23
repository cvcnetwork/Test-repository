# Test-repository
Test repository Adarsh

SELECT  
date, campaign_id
from yandex_ext.video_performance_report
WHERE date= 'date to check'
group by campaign_id, date order by campaign_id,date
