# Advertising Policy --- 21

**Developer:** Brlek

## Free version

The free version of 21 may use Google AdMob.

Planned advertising: - Interstitial advertisement approximately every 10
completed games - Optional rewarded advertisement when a user wants an
additional reroll after the free daily allowance

## Rewarded ads

Rewarded ads are optional.

A user must choose to watch the rewarded ad to receive the advertised
reward.

The reward should only be granted after a valid completion signal from
the advertising provider.

## Interstitial ads

Interstitial ads must not interrupt active gameplay or a critical player
action.

A preferred placement is after the result screen and before returning to
the main menu.

Do not show an interstitial: - During an active draft - During an active
online match - While the result is being calculated - Before the app's
loading screen - In a way that unexpectedly interrupts a user's current
action

Google Play's ads policy specifically restricts unexpected full-screen
interstitials during gameplay and permits opt-in rewarded ads and
appropriate post-result placements. citeturn0search7turn0search13

## Premium

Lifetime Premium is intended to remove normal/interstitial and rewarded
advertising requirements.

## Advertising data

Google AdMob may process advertising/device information according to
Google's applicable policies and the SDK configuration.

The final Privacy Policy and Google Play Data safety declaration must
match the actual production AdMob implementation.

## Configuration

Keep ad frequency and reward limits configurable rather than hard-coded
throughout the game.

Suggested configuration: - `NORMAL_AD_GAME_INTERVAL = 10` -
`FREE_DAILY_REROLLS = 3` - `PREMIUM_DAILY_REROLLS = 30`

The actual production values should be controlled by the
server/configuration layer where appropriate.
