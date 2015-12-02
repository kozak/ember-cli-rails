# Ruby support

According to [these release notes][1.9.3-eol], Ruby versions prior to `2.0.x`
has been end-of-lifed.

Additionally, this codebase makes use of [(required) keyword arguments][kwargs].

From `ember-cli-rails@0.4.0` and on, we will no longer support versions of Ruby
prior to `2.1.0`.

To use `ember-cli-rails` with older versions of Ruby, try the `0.3.x` series.

[kwargs]: https://robots.thoughtbot.com/ruby-2-keyword-arguments
[1.9.3-eol]: https://www.ruby-lang.org/en/news/2015/02/23/support-for-ruby-1-9-3-has-ended/

# Rails support

According to the [Rails Maintenance Policy][version-policy], Rails versions
prior to `3.2.x` have been end-of-lifed. Additionally, the `4.0.x` series no
longer receives bug fixes of any sort.

From `ember-cli-rails@0.4.0` and on, we will no longer support versions of Rails
prior to `3.2.0`, nor will we support the `4.0.x` series of releases.

From `ember-cli-rails@0.6.0` and on, we will no longer support versions of Rails
prior to `4.1.0`.

To use `ember-cli-rails` with older versions of Rails, try the `0.3.x` series.

[version-policy]: http://guides.rubyonrails.org/maintenance_policy.html
