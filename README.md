# gymcredits

Automated computer system for managing gyms.

## Specifications


- The gym will have users, uniquely identified by a UUID, meant to be embedded
  into a QR code that is scanned to allow entry to the gym. An unique email
  or another way to identify the user will be needed as a recovery method for
  lost gym licenses.
- There will be a credit system, where each user will spend 1 credit to enter
  to the gym.

### About credit system

- The credits are transferrable, meaning a user can pass or gift credits to
  another users.
- The credits are attached to a user, so a user can pay with its credits for
  the entry of any people.
- The credits can be purchased individually or in packs.
- The credits expire within a preferred interval from purchase, their expiration
  date doesn't change when they're transferred.
