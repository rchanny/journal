# journal
1. Add to common.py 'lms.djangoapps.journal',
2. Have not changed journal.html to include journal listing in dashboard 
3. Add to urls.py     
url(r'^journal/?$', journal_views.student_journal, name='journal'),
from lms.djangoapps.journal import views as journal_views
