# backend-continuation-
learning about backend

@admin.register(Post)
class ArticlePost(admin.ModelAdmin):
list_filter = ('name')

list filter-The admin panel will be filtered by type

list display divides according to the type in the table on the admin panel 
