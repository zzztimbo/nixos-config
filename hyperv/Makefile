.PHONY: pull 
pull: 
	@echo 'pulling...' 
	rsync -avzh ${TARGET_USER}@${TARGET_HOST}:/etc/nixos/. .

.PHONY: ssh 
ssh: 
	ssh ${TARGET_USER}@${TARGET_HOST} 
