# AWS활용한 노트 앱 (풀스택)
# 사용한 스택
1. 리액트
2. Amplify CLI
3. Auth && amplify ui-react
4. GraphQL
5. Storage

# Cannot find file './aws-exports' in './src'. Error
-> 앱설정 -> 빌드 설정 -> 
version: 1
backend:
  phases:
    build:
      commands:
        - '# Execute Amplify CLI with the helper script'
        - amplifyPush --simple

-> continuous deploys set up (staging) 설정

