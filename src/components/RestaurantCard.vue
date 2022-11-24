<template>
  <div class="restaurant--card">
    <div class="restaurant--image">

    </div>
    <div class="restaurant--informations">
        <div class="top">
            <p class="name">
                ShopTonBarber
            </p>
            <p class="note">
                <span>
                    4.5
                </span>
            </p>
        </div>
        <p class="time">
            20-30min
        </p>
    </div>
  </div>
</template>

<script>
export default {
    name: "RestautantCard",
}
</script>

<style lang="scss">
    .restaurant--card {
        width: 30%;
        height: 40vh;

        p {
            margin: 0;
        }
        .restaurant--image {
            background-image: url("https://images.unsplash.com/photo-1442595449221-4697415c7fe0?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80");
            height: 70%;
            background-size: cover;
            background-position: center;
            
        }

        .restaurant--informations {
            .top {
                margin: 10px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;

                .note {
                    background-color: #F6E7D8;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    height: 30px;
                    width: 30px;
                    font-style: 0.8rem;
                    border-radius: 50%;
                }
            }

            .time {
                font-size: 0.9rem;
            }
        }
    }
</style>