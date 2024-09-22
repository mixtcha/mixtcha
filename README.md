# mixtcha
quickly mix LLMs together


## Mixtcha Confgurations

Three ways to configure the mixtcha. 

1. Use an official mixtcha by name in `body.model`
2. Provide a URL to a Mixtcha configuration YAML file as `X-Mixtcha-Config-Url`
3. Write the configuration directly to `X-Mixtcha-Config`

Precedence. Higher on this list will overwrite lower, if multiple are present.
1. `X-Mixtcha-Config`
2. `X-Mixtcha-Config-Url`
3. `body.model`