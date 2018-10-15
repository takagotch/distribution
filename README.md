### distribution
---
https://github.com/docker/distribution

.rb
https://github.com/clbustos/distribution

```
gem install distribution
gem install rb-gsl

# lib/distribution
distribution --new your_distribution
```

```ruby
pdf = Distribution::Normal.pdf(x)
cdf = Distribution::Normal.cdf(x)
pv = Distribution::Normal.p_value(x)
p = Distribution::T.cdf(x)
include Distribution::Shorthand
tdist_cdf(x)

Distribution::<name>.(cdf|pdf|p_value|rng)
Distribution::<name>.exact_(cdf|pdf|p_value)
<Distribution shortname>_(cdf|pdf|p|r)
<Distribution shortname>_(ecdf|epdf|ep)
```

