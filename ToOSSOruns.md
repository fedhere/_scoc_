

**Simulate SSO ToO**

**SCHEMA (different from earlier simulations):**

1) simulate 3xNtriggers where Ntrigger is the number of recommended triggers as all-sky events.
2) follow up any of the area that is visible, regardless of the location of the trigger
3) simulate
- 1 run with 3x3/4xNtriggers
- 1 run with 3x4/5xNtriggers
- 1 run with 3xNtriggers
- 1 run with 3x6/5xNtriggers
- 1 run with 3x5/4xNtriggers

**Ntriggers** = 300 (30/year) triggers

**Area**: 10 sq deg

* Night 0:

      if not twilight:

            2xr x 3 passes separated by 33 minutes with dither between the two 30s observations
      else:

          2xz @ 15sec x 3 passes separated by 33 minutes with dither between the two 15s observations

