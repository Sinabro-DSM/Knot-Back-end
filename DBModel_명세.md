# User Schema

- email (PK)
    - string

- includedWS
    - string

- inviteWS
    - array
        - WSName
            - string


# WS Schema

- WSName
    - string

- image
    - fileName

- inviteLog
    - array
        - email

- WSUser
    - isCaptain
        - boolean
    
    - displayName
        - string
    
    - Image
        - fileName
    
    - email (user Schema)

- page

    - block
        - array
            - _id
                - string

    - title
        - string

    - emoji
        - string

    - _id
        - string
    
    - upPage
        - _id
    
    - md
        - _id
            - string

        - text
            - string
    
    - todo
        - _id
            - string
        
        - text
            - string
        
        - isChecked
            - boolean
    
    - link
        - _id
            - string

        - text
            - string

        - goto
            - string

- MemberList
    - displayName
        - string
    
    - email (user Schema)
        - string
    
    - Image
        - fileName

    - isCaptain
        - Boolean
