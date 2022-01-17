## Title
ToDo app with authentication in django



##
Installation

pip install django

##
Usage

Import django.urls

import Views




##
Example

urlpatterns = [
    path('login/', CustomLoginView.as_view(), name='login'),
    path('logout/', LogoutView.as_view(next_page='login'), name='logout'),
    path('register/', RegisterPage.as_view(), name='register'),
    ]
urlpatterns = [
    path('admin/', admin.site.urls),
    path('', include('base.urls')),
]    



![image](https://user-images.githubusercontent.com/79367834/149776401-0634b0fc-131c-4239-8bc6-9b2c8cd36d97.png)
