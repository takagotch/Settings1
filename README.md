### Settings1
---

https://bitbucket.org/takagotch/rails-1st-settings/src/master/



```cmd
rails g controller top index
vi app/controllers/top_controller.rb
vi config/routes.rb
curl https://localhost:3000/
rails s
vi app/views/top/index.html.erb

vi config/routes.rb
vi app/controllers/top_controller.rb
vi app/views/top/abou.html.erb
curl https://localhost:3000/
vi app/views/layouts/application.html.erb
app/helpers/application_helper.rb
vi app/views/layouts/application.html.erb

vi app/views/shared/_header.html.erb
vi app/helpers/application_helper.rb
vi app/views/shared/_sidebar.html.erb
vi app/views/shared/_login_form.html.erb
vi app/views/shared/_footer.html.erb
vi app/views/top/index.html.erb
vi app/controllers/top_controller.rb
vi app/assets/sytlesheets/application.css
vi app/app/assets/stylessheets/application.css
vi app/assets/stylesheets/application.css
vi app/assets/stylesheets/application.css
```

```cmd
vi config/database.yml
rails db:create
rails db:create RAILS_ENV=production
rails db:drop
vi config/application.rb
rails -T
rails g model member
vi db/migrate/202007312150_create_member.rb
rails db:migrte
rails db:migrate RAILS_ENV=production
//
rails g migration ModifyMembers
rails db:migrate VERSION=202007312150
rails db:migrate:status
rails db:migrate:reset

rails c
```

```
rails g controller members
vi app/views/shared/_header.html.erb
vi app/controllers/members_controller.rb
vi app/views/members/index.html.erb
vi app/assets/table.css
vi app/views/members/index.html.erb
vi app/views/members/index.html.erb
vi app/views/members/index.html.erb
vi config/routes.rb
vi app/controllers/members_controller.rb
vi app/models/member.rb
vi app/views/members/index.html.erb
vi app/controllers/members_controller.rb
vi app/views/members/show.html.erb

vi app/controllers/members_controller.rb
mkdir -p app/views/members
vi app/views/members/edit.html.erb
vi app/views/members/_form.html.erb
vi app/views/members/new.html.erb
vi app/views/members/edit.html.erb

vi config/application.rb
vi app/controllers/members_controller.rb
vi app/views/layouts/application.html.erb
vi app/assets/stylesheets/flash.css
vi app/controllers/members_controller.rb
vi app/controller/members_controller.rb
vi app/views/members/index.html.erb

vi app/modesl/members.rb
vi app/modesl/members.rb
vi app/modesl/members.rb

vi app/modesl/members.rb
vi app/modesl/members.rb

vi app/views/shared_errors.html.erb
vi app/views/members/_form.html.erb

vi config/application.rb
vi Gemfile
bundle install

vi config/locales/ja.yml
vi app/views/members/_form.html.erb
vi config/locales/ja.yml
vi app/models/members.rb
```

```
vi rails test test/models/member_test.rb
vi test/controllers/member_controller_test.rb
rails test test/controllers/members_controller_test.rb
rails test:models
rails test:controllers
rails test
vi test/models/member_test.rb
rails test test/models/member_test.rb

vi Gemfile
bundle install
vi test/factories/members.rb
vi test/models/member_test.rb

vi config/route.rb
rails g model article
vi db/migrate/202007312150_create_article.rb
rails db:migrate
vi test/factories/articles.rb
vi db/seeds.rb
vi db/seeds/development/articles.rb
vi test/models/article_test.rb
rails test test/models/article_test.rb
vi app/models/article.rb
rails test test/models/article_test.rb
vi test/models/article_test.rb
vi app/models/article.rb
vi test/models/article_test.rb
vi app/models/article.rb
vi config/locales/ja.yml
vi test/models/article_test.rb
vi app/models/article.rb
vi app/models/article.rb
vi app/models/article.rb
vi test/models/article_test.rb
vi app/models/article.rb
vi app/models/article.rb
vi app/views/shared/_sidebar.html.erb

rails g controller articles
vi test/controllers/articles_controller_test.rb
vi app/controllers/articles_controller.rb
vi app/views/articles/index.html.erb
vi app/views/shared/_header.html.erb
vi test/controllers/articles_controller_test.rb
vi app/controllers/articles_controller.rb
vi app/views/articles/show.html.erb
rails test test/controllers/articles_controller_test.rb
vi test/controllers/articles_controller_test.rb
vi app/views/articles/new.html.erb
vi app/views/articles/edit.html.erb
vi app/views/articles/_form.html.erb
vi config/locales/ja.yml
vi test/controllers/articles_controller_test.rb
vi app/controllers/articles_controller.rb
vi test/controllers/articles_controller_test.rb
vi test/controllers/articles_controller_test.rb
vi app/controllers/articles_controller.rb
vi test/controllers/top_controller_test.rb
vi app/controllers/top_controller.rb
vi app/views/top/index.html.erb

rails g integration_test manage_articles
vi test/integration/manage_articles_test.rb
rails test:integration

export RAILS_ENV=production
export RAILS_SERVE_STATIC_FILES=1
set RAILS_ENV=production
set RAILS_SERVE_STATIC_FILES=1
rails secret > secret.key
export SECRET_KEY_BASE=$(cat secret.key)
set /p SECRET_KEY_BASE=<secret.key
rails assets:precompile
rails db:setup
rails s

vi app/assets/stylesheets/application.css
vi app/assets/stylesheets/common.css.scss
vi app/assets/stylesheets/table.css.scss
vi app/assets/javascripts/application.js
vi app/assets/javascripts/utility.js.coffee
vi app/views/articles/_form.html.erb
```

```
vi app/models/member.rb
vi app/views/members/_form.html.erb
vi config/locales/ja.yml
vi app/models/member.rb
vi Gemfile
bundle install
rails g migration ModifyMembers1
vi db/migrate/202007312238_modify_members1.rb
vi rails db:migrate
vi app/models/member.rb
vi test/factories/members.rb
vi db/seeds/development/members.rb
rials db:reset
vi test/models/member_test.rb
vi app/models/member.rb
vi config/routes.rb
rails g controller sessions
vi app/controllers/sessions_controller.rb
vi app/controllers/application_controller.rb
vi app/views/shared/_login_form.html.erb
vi app/views/shared/_sidebar.html.erb
vi app/views/shared/_header.html.erb
vi app/views/shared/_header.html.erb
vi app/controllers/application_controller.rb
vi app/controllers/members_controller.rb
vi app/views/articles/index.rb
vi app/controllers/articles_controller.rb
vi app/models/article.rb
vi app/views/shared/_sidebar.html.erb
vi db/seeds/development/articles.rb
vi test/test_helper.rb
vi test/controllers/members_controller_test.rb
vi test/controllers/articles_controller_test.rb
rails g integration_test user_authentication
vi test/integration/user_authentication_test.rb
vi test/integration_test_helper.rb
vi test/integration/manage_articles_test.rb
rails test:integration
vi app/controllers/members_controller.rb
vi app/views/members/_form.html.erb
vi config/application.rb
vi app/controllers/members_controller.rb
vi app/controllers/members_controller.rb
vi app/controllers/articles_controller.rb
vi config/routes.rb
rails routes
rails g controller accounts show edit
vi app/controllers/accounts_controller.rb
vi app/views/members/_body.html.erb
vi app/views/members/show.html.erb
vi app/views/accounts/show.html.erb
vi app/views/shared/_header.html.erb
vi app/views/accounts/edit.html.erb
vi app/views/members/_form.html.erb
vi app/controllers/account_controller.rb

vi app/controllers/application_controller.rb
vi app/controllers/application_controller.rb
vi app/controllers/application_controller.rb
vi app/views/layouts/error.html.erb
vi app/views/errors/bad_request.html.erb
vi app/views/errors/forbidden.html.erb
vi app/views/errors/not_found.html.erb
vi app/views/errors/internal_server_error.html.erb
curl https://localhost:3000/members
curl https://localhost:3000/articles/100  // ERR

vi config/routes.rb
vi app/controllers/top_controller.rb
vi config/routes.rb
vi app/controllers/top_controller.rb
vi test/controllers/members_controller_test.rb
vi test/controllers/articles_controller_test.rb

vi Gemfile
bundle install
vi config/locales/ja.yml
vi app/controllers/members_controller.rb
vi app/views/members/index.html.erb
vi db/seeds/development/members.rb
vi app/assets/stylesheets/pagination.css.scss
vi app/controllers/articles_controller.rb
vi app/views/articles/index.html.erb
vi db/seeds/development/articles.rb
```

```
rails g model entry
vi db/migrate/202007312321_create_entries.rb
rails db:migrate
rails db:migrate:reset
vi app/models/member.rb
vi app/models/entry.rb
vi config/routes.rb
vi config/locales/ja.yml
vi app/models/entry.rb
vi app/models/entry.rb
vi app/models/entry.rb
vi db/seeds.rb
vi db/seeds/development/entries.rb
rails db:reset
rails g controller entries index show new edit
vi app/controllers/entries_controller.rb
vi app/views/entries/index.html.erb
vi app/views/entries/_footer.html.erb
vi app/views/shared/_header.html.erb
vi app/views/entries/show.html.erb
vi app/views/shared/_sidebar.html.erb
vi app/controllers/entries_controller.rb
vi app/views/entries/new.html.erb
vi app/views/entries/edit.html.erb
vi app/views/entries/_form.html.erb
vi app/controllers/entries_controller.rb
vi app/controllers/entries_controller.rb
rails g model member_image
vi db/migrate/202007312326_create_member_images.rb
rails db:migrate
vi app/models/member.rb
vi app/models/member_image.rb
vi app/models/member_image.rb
vi app/models/member_iamge.rb
vi app/models/member_image.rb
vi app/models/member_image.rb
vi config/locales/ja.yml
vi config/locales/ja.yml
vi db/seeds/development/members.rb
rails db:reset

```

```
```

```
```

