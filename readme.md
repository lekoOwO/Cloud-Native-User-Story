# Cloud-Native-User-Story

## User Story

- As a user, I would want to redeem coupons.

    ### Acceptance Criterias
        
        - Given: User logged in and navigated to the coupon page.
          When:  User tried to redeem a valid coupon. 
          Then:  User redeems the coupon. Show the success page.

        - Given: User logged in and navigated to the coupon page.
          When:  User tried to redeem a invalid coupon. 
          Then:  Failed. Show the error message.

- As a user who cannot make decision, I want the recommendation to help me decide.
    ### Acceptance Criterias
        
        - Given: User navigated to the selection page.
        - When: User tried to access a feature
        - Then: Highlight the selection item according to user's past behavior.
