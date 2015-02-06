* Bundles from Symfony Standard distribution
* Sonata Admin Bundles: Admin and Doctrine ORM Admin
* Sonata Ecommerce Bundles: Payment Customer Invoice Order and Product
* Sonata Foundation Bundles: Core Notification Formatter Intl Cache Seo and Easy Extends
* Sonata Feature Bundles: Page Media News User Block Timeline
* Api Bundles: FOSRestBundle BazingaHateoasBundle NelmioApiDocBundle and JMSSerializerBundle
 
les commandes de console
	app/console cache:warmup --env=prod --no-debug'
    app/console cache:create-cache-class --env=prod --no-debug'
    app/console doctrine:database:drop --force'
    app/console doctrine:database:create'
    app/console doctrine:schema:update --force'
    app/console doctrine:fixtures:load'
    app/console sonata:news:sync-comments-count'
    app/console sonata:page:update-core-routes --site=all --no-debug'
    app/console sonata:page:create-snapshots --site=all --no-debug'
    app/console assets:install --symlink web'
    app/console sonata:admin:setup-acl'
    app/console sonata:admin:generate-object-acl'