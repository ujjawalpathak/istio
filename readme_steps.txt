STEP1: istioctl manifest apply -f new_profile.yaml
STEP2: kubectl apply -f kiali.yaml
STEP3: kubectl apply gateway_default.yaml
STEP4: CREATE DEPLOYMENTS
STEP5: ./attach_loadBlanacer.sh
