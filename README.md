Plugin Phong Ấn ( Leak Làng Băng Plugin )

Command:

/lockeditem reload
/phongan



config.yml:

lock:
  # Position là vị trí của lore sẽ xuất hiện trên vật phẩm
  # Có 2 loại position là:
  #  TOP: Vị trí của lore sẽ ở trên đầu
  #  BOTTOM: Vị trí của lore sẽ ở cuối cùng
  position: BOTTOM
  lore:
    - ' '
    - '&7Chủ sở hữu: &c%player%'
    - '&cVật phẩm đã bị khoá.'

messages:
  drop: '&cBạn không thể thả vật phẩm đã bị khóa.'
  place: '&cBạn không thể đặt vật phẩm đã bị khóa xuống đất được!'
  no-perm: '&cBạn không có quyền để sử dụng lệnh này!'
  lock: '&aĐã khóa vật phẩm trên tay.'
  unlock: '&aĐã mở khóa vật phẩm trên tay.'
  not-owner: '&cBạn không phải chủ sở hữu của vật phẩm này!'
  empty-hand: '&eBạn phải cầm ít nhất 1 vật phẩm ở trên tay để thực hiện việc này.'
  reload: '&aĐã tải lại config!'
  ah-sell: '&cBạn không thể đăng bán vật phẩm đã được khóa lên chợ đen!'
  require-custom-name: '&cBạn cần phải đổi tên của vật phẩm này ít nhất 1 lần!'
  help:
    - '&7/&alockeditem &areload &8&oTải lại config của plugin'
