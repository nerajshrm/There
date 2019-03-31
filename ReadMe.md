## yet to finish


change made to create superuser,
before was causing error

./drf_user/models/
class name = User

line 21
update_date = cmodels.UnixTimestampField(_('Date Modified'),auto_now=True, auto_created=True)

auto_now=True # this is changed to
auto_now_add=True

Inference==
Everything is working good just /admin/ url is not letting superuser to signin
